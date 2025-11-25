CYPRUS INTERNATIONAL UNIVERSITY
FACULTY OF ENGINEERING
CMPE343 – Database Management Systems and Programming I
Lab 5
1) -- Create the staff table
 CREATE TABLE staff (
 staff_id INT PRIMARY KEY,
 first_name VARCHAR(50),
 last_name VARCHAR(50),
 salary DECIMAL(10, 3)
 );
 -- Insert sample data into the staff table
 INSERT INTO staff (staff_id, first_name, last_name, salary)
 VALUES
 (1, 'Alex', 'Miller', 55000.123),
 (2, 'Emily', 'Johnson', 60000.456),
 (3, 'Max', 'Smith', 70000.789),
 (4, 'Sophia', 'Brown', 48000.321),
 (5, 'Oliver', 'Davis', 72000.000);
2) Write a query to display the staff_id along with the concatenated full name for each
person. Use the CONCAT function to combine the first and last names, and alias the
concatenated result as 'FULL_NAME'.
3) Write a query to display the first name, last name, length of the last name using the
LENGTH function.
4) Write a query to display all the columns, and the position of the first occurrence of the
letter 'e' in the first name using the INSERT function.
5) Write a query to display the staff_id and the salary values truncated to two decimal
places for each staff member from the 'staff' table. Use the 'TRUNCATE' function to
achieve this.
6) Write a query to display the employee_id and the rounded salary values for each
employee. Round the salary values to the nearest whole number using the ROUND
function. Name the rounded salary column as 'rounded_salary'.
