CREATE TABLE Employee(
    EmployeeId INT PRIMARY KEY auto_increment,
    Firstname VARCHAR(100),
    Lastname VARCHAR(100),
    Age INT,
    City VARCHAR(100),
    Salary DECIMAL(10,2)
);

INSERT INTO Employee(Firstname, Lastname, Age, City, Salary)
VALUES('Kalai', 'Marshall', 25, 'Chennai', 150000.00),
      ('Selva', 'Ganesh', 25, 'Delhi', 65000.00),
      ('Vicky', 'Kumar', 25, 'Kerala', 140000.00),
      ('Praveen', 'Kumar', 25, 'Bangalore', 77000.00),
      ('Anbu', 'Arasan', 25, 'Chennai', 56000.00),
      ('Vineeth', 'Gulapaly', 25, 'Chennai', 90000.00);

SELECT * FROM Employee;

-- Write a query to retrieve the details of employees who are older than 20 years.
SELECT * FROM Employee Where Age>20;

-- Write a query to retrieve all employee data sorted by Salary in descending order.
SELECT * FROM Employee Order by Salary desc;

-- 6. Update Salary of an Employee
-- Write a query to update the Salary of the employee with EmployeeID = 3 to 55000.00.
Update Employee 
SET Salary=55000 where EmployeeId=3;
SELECT * FROM Employee where EmployeeId=3;

-- 7. Delete an Employee Record
-- Write a query to delete the employee record where EmployeeID = 5.
Delete from Employee
Where EmployeeId=5; 
SELECT * FROM Employee;

-- 8. Add a New Employee
-- Write a query to insert a new employee 
-- record for Nikita Ramesh, age 30, from Chennai, with a salary of 68000.
INSERT INTO Employee (Firstname, Lastname, Age, City, Salary)
Values ('Nikita','Ramesh',30,'Chennai',68000.00);
SELECT * FROM Employee;

-- 9. Retrieve Employees Who Have a Salary Greater Than 60000
-- Write a query to retrieve employees whose Salary is greater than 60000.
SELECT * FROM Employee Where Salary>70000;

-- 10. Count the Number of Employees in Each City
-- Write a query to count how many employees are from each City.
Select City,COUNT(EmployeeId) FROM Employee GROUP BY City;

