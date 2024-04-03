# Sql_server_Assignment
Created a table named Customers with columns: CustomerID, FirstName, LastName, Email, and PhoneNumber.
Created a table named Orders with columns: OrderID, CustomerID, OrderDate, and TotalAmount.
Created a table named OrderDetails with columns: OrderDetailID, OrderID, ProductID, Quantity, and UnitPrice.
Created a table named Products with columns: ProductID, ProductName, UnitPrice, and InStockQuantity.

Inserted sample data into the Customers, Products, OrderDetails, and Orders tables

task 1 :Then created a login and user Order_Clerk with permission to insert new orders and update order details in the Orders and OrderDetails tables ..
 task2:Then created a table Stock_Update_Audit which will store data of updated Product with the time of action done.
 Task three  also done in task 3 i have joined the tables  Customers and Orders tables and write a query which return the specified col which i have called in th query.
 Task 4 was completed in this task . In this task i have joined multiple tables(Products AS p ,OrderDetails AS o, &  Orders AS b ) and use and aggregate function which return  total amount greater than the average total amount of all orders.
 Task 5 completed :  i creat a stored produre called GetOrdersByCustomer with  @CustomerID as a parameter and joind two table (Orders as o inner join OrderDetails as q) to retrieve required columns ..

 Task 6 completed  created a view named OrderSummary that displays the OrderID, OrderDate, CustomerID, and TotalAmount from the Orders table.
 Task 7 completed Created a view named ProductInventory that shows the ProductName and InStockQuantity from the Products table..
 task 8 done: joined the OrderSummary view with the Customers table to retrieve the customer's first name and last name along with their orderdetails.
