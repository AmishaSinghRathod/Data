**SQL** : Structured Query Language
**INTRO** : SQL is a standard language for accessing and manipulating databases.

RDBMS : Relational Database Management System.
INTRO : stands for Relational Database Management System.

SQL Syntax : A database most often contains one or more tables. Each table is identified by a name (e.g. "Customers" or "Orders"). Tables contain records (rows) with data.
Query : SELECT * FROM Customers;

SELECT : The SELECT statement is used to select data from a database.
Ouery : SELECT CustomerName,City FROM Customers;

Update : The UPDATE statement is used to modify the existing records in a table.
Ouery : UPDATE Customers
SET ContactName='Alfred Schmidt', City='Frankfurt'
WHERE CustomerID=1;

DELETE : statement is used to delete existing records in a table.
Query : DELETE FROM Customers WHERE CustomerName='Alfreds Futterkiste';

Insert into : The INSERT INTO statement is used to insert new records in a table.
Query : INSERT INTO Customers (CustomerName, ContactName, Address, City, PostalCode, Country)
VALUES ('Cardinal','Tom B. Erichsen','Skagen 21','Stavanger','4006','Norway');

Distinct : The SELECT DISTINCT statement is used to return only distinct (different) values.
Ouery : SELECT Country FROM Customers;

Where : The WHERE clause is used to filter records.
Query : SELECT * FROM Customers
WHERE Country='Mexico';

SQL AND, OR and NOT : The WHERE clause can be combined with AND, OR, and NOT operators.
Query : SELECT * FROM Customers
WHERE Country='Germany' AND (City='Berlin' OR City='München');

Order by : The ORDER BY keyword is used to sort the result-set in ascending or descending order.
Query : SELECT * FROM Customers
ORDER BY Country ASC, CustomerName DESC;

Null : A field with a NULL value is a field with no value.
Query : SELECT CustomerName, ContactName, Address
FROM Customers
WHERE Address IS NULL;
















