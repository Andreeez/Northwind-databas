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



