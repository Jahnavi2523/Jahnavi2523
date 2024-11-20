CREATE DATABASE sampleDB;

USE sampleDB;

CREATE TABLE employees (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(50),
    position VARCHAR(50),
    salary DECIMAL(10, 2)
);

INSERT INTO employees (name, position, salary)
VALUES
('John Doe', 'Manager', 50000.00),
('Jane Smith', 'Developer', 40000.00),
('Alice Johnson', 'Designer', 35000.00);



<!---
Jahnavi2523/Jahnavi2523 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
