Insert into Categories 

INSERT INTO Categories VALUES 
(1, 'Beverages', 'Soft drinks'), 
(2, 'Condiments', 'Sweet and savory sauces'); 
Insert into Customers 

INSERT INTO Customers VALUES 
(1, 'Alfreds Futterkiste', 'Maria Anders', 
'Obere Str. 57', 'Berlin', '12209', 'Germany'), 
 
(2, 'Ana Trujillo Emparedados y helados', 
'Ana Trujillo', 'Avda. de la Constitución 2222', 
'Mexico D.F.', '05021', 'Mexico'); 

INSERT INTO Employees VALUES 
(1, 'Davolio', 'Nancy', '1968-12-08', 
'EmpID1.pic', 'Sales Representative'), 
 
(2, 'Fuller', 'Andrew', '1952-02-19', 
'EmpID2.pic', 'Vice President'); 

 NSERT INTO Shippers VALUES 
(1, 'Speedy Express', '(503) 555-9831'), 
 
(2, 'United Package', '(503) 555-3199'); 
INSERT INTO Suppliers VALUES 
(1, 'Exotic Liquid', 'Charlotte Cooper', 
'49 Gilbert St.', 'London', 'EC1 4SD', 
'UK', '(171) 555-2222'), 
 
(2, 'New Orleans Cajun Delights', 
'Shelley Burke', 'P.O. Box 78934', 
'New Orleans', '70117', 'USA', 
'(100) 555-4822'); 
 INSERT INTO Products VALUES 
(1, 'Chais', 1, 1, 
'10 boxes x 20 bags', 18.00), 
 
(2, 'Chang', 1, 1, 
'24 - 12 oz bottles', 19.00);

INSERT INTO Orders VALUES 
(10248, 1, 1, '2024-01-10', 1), 
 
(10249, 2, 2, '2024-01-11', 2); 

INSERT INTO OrderDetails VALUES 
(1, 10248, 1, 12), 
 
(2, 10249, 2, 10);  
