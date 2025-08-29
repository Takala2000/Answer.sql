SELECT checkNumber, paymentDate, amount
FROM payments;

SELECT orderDate, requiredDate, status
FROM orders
WHERE status = 'In Process'
ORDER BY orderDate DESC;

SELECT firstName, lastName, email
FROM employees
WHERE jobTitle = 'Sales Rep'
ORDER BY employeeNumber DESC;

SELECT *
FROM



SELECT productName, quantityInStock
FROM products
ORDER BY buyPrice ASC
LIMIT 5;



Question 1: Create a table named student
CREATE TABLE student (
    id INTEGER PRIMARY KEY,
    fullName TEXT(100),
    age INTEGER
);

Question 2: Insert at least 3 records into the student table
INSERT INTO student (id, fullName, age)
VALUES
(1, 'John Doe', 18),
(2, 'Jane Smith', 19),
(3, 'Bob Johnson', 21);

Question 3: Update the age of the student with ID 2 to 20
UPDATE student
SET age = 20
WHERE id = 2;
