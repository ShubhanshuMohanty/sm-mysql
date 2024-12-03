# MySQL Employee Database Operations

This document contains the SQL commands to create a database, table, and perform CRUD operations on an `Emp` table.

---

## Step 1: Create a Database

```sql
-- Create a new database named EmployeeDB and use it
CREATE DATABASE EmployeeDB;
USE EmployeeDB;
```
## Step 2: Create the `Emp` Table

```sql
-- Create a table named Emp with the following columns
CREATE TABLE Emp (
    EmpId INT PRIMARY KEY,       -- Employee ID (Primary Key)
    EmpName VARCHAR(45),         -- Employee Name
    Role VARCHAR(30),            -- Employee Role
    Salary BIGINT                -- Employee Salary
);
```
## Insert Data

```sql
INSERT INTO Emp (EmpId, EmpName, Role, Salary) VALUES 
(1, 'Alice', 'Manager', 80000),
(2, 'Bob', 'Developer', 60000),
(3, 'Charlie', 'Analyst', 50000),
(4, 'Diana', 'Designer', 55000),
(5, 'Eve', 'Tester', 45000);
```
## Select Queries

---

### 1. Select All Data

```sql
SELECT * FROM Emp;
```
| EmpId | EmpName  | Role       | Salary  |
|-------|----------|------------|---------|
| 1     | Alice    | Manager    | 120000  |
| 2     | Bob      | Developer  | 80000   |
| 3     | Charlie  | Tester     | 60000   |
| 4     | Diana    | Developer  | 75000   |
| 5     | Eve      | HR         | 50000   |
