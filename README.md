Select the database : 

Use Boitumelo_240757610; 
CREATE TABLE Customers ( 

    CustomerID INT PRIMARY KEY, 

    CustomerName VARCHAR(255), 

    ContactName VARCHAR(255), 

    Address VARCHAR(255), 

    City VARCHAR(100), 

    PostalCode VARCHAR(20), 

    Country VARCHAR(100) 

); 
CREATE TABLE Categories ( 

    CategoryID INT PRIMARY KEY, 

    CategoryName VARCHAR(255), 

    Description TEXT
CREATE TABLE Employees ( 

    EmployeeID INT PRIMARY KEY, 

    LastName VARCHAR(255), 

    FirstName VARCHAR(255), 

    BirthDate DATE, 

    Photo VARCHAR(255), 

    Notes TEXT 
CREATE TABLE OrderDetails ( 

    OrderDetailID INT PRIMARY KEY, 

    OrderID INT, 

    ProductID INT, 

    Quantity INT 

); 
