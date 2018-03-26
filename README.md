# Northwind-databas

#1 SELECT DISTINCT Country FROM `Employees`;

#2 SELECT CategoryID, CategoryName FROM `Categories`ORDER BY CategoryName DESC;

#3 SELECT CompanyName, ContactName, Phone, Fax FROM `Customers` WHERE Country = "Germany" ORDER BY CompanyName DESC;

#4 SELECT City FROM `Customers` WHERE Country = "Sweden";

#5 SELECT ProductName FROM `Products` WHERE ProductName LIKE "%Br-d%";

#6 SELECT FirstName, LastName FROM `Employees` WHERE BirthDate = "1966-01-27";

#7 SELECT FirstName, LastName FROM `Employees` WHERE ReportsTo IS NULL;

#8 SELECT ProductName, UnitsInStock, ReorderLevel FROM `Products` WHERE UnitsInStock < ReorderLevel;

#9 SELECT CompanyName, ContactName, Country, Phone, HomePage FROM `Suppliers` WHERE Country = "Germany" OR Country ="France" ORDER BY CompanyName DESC

#10 SELECT ProductID, ProductName, UnitPrice, UnitsInStock FROM `Products` WHERE UnitsInStock > 100 ORDER BY UnitPrice DESC, UnitsInStock ASC

#11 SELECT BirthDate FROM `Employees` ORDER BY BirthDate LIMIT 1;

#12 SELECT AVG(UnitPrice) AS "Snittpris", SUM(UnitPrice) AS "Summa" FROM Products WHERE CategoryID = 2;

#13 SELECT Discount AS "StörstRabatt" FROM `Order_Details` ORDER BY Discount DESC LIMIT 1;

#14 SELECT COUNT(CategoryID) AS "Antal" FROM `Categories`;

#15 SELECT Country, COUNT(*) AS "Antal" FROM `Customers` GROUP BY Country ORDER BY Antal DESC

#16 SELECT SupplierID, AVG(UnitPrice) AS "Snittpris" FROM `Products` WHERE CategoryID IN (1,3,5,7) GROUP BY SupplierID;

#17 SELECT CategoryID FROM `Products` GROUP BY CategoryID HAVING COUNT(*) > 10

#18 SELECT CustomerID, COUNT(*) AS AntalOrder FROM `Orders` WHERE OrderDate > "1998-01-01" AND OrderDate < "1998-12-31" GROUP BY CustomerID HAVING AntalOrder > 10

#19 SELECT OrderID, SUM(UnitPrice*Quantity) AS OrderSumma FROM `Order_Details` WHERE OrderID > 10500 GROUP BY OrderID HAVING OrderSumma < 10000 ORDER BY OrderSumma DESC

#20 SELECT ProductID, SUM(Quantity) FROM `Order_Details` GROUP BY ProductID ORDER BY SUM(Quantity) DESC LIMIT 10

#21 
    




