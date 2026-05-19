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
CREATE TABLE OrderDetails ( 

    OrderDetailID INT PRIMARY KEY, 

    OrderID INT, 

    ProductID INT, 

    Quantity INT 
CREATE TABLE Products ( 

    ProductID INT PRIMARY KEY, 

    ProductName VARCHAR(255), 

    SupplierID INT, 

    CategoryID INT, 

    Unit VARCHAR(255), 

    Price DECIMAL(10,2) 
CREATE TABLE Shippers ( 

    ShipperID INT PRIMARY KEY, 

    ShipperName VARCHAR(255), 

    Phone VARCHAR(50) 

); 
