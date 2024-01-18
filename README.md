# Data-Manipulation-using-SQL
The fundamental concepts of Data Definition Language (DDL) in Database Management Systems (DBMS). 


Instructions:

1. Create a Database:

Create a new database named "UniversityDB".
Ensure that the database creation is successful.

2. Create Tables:

Within the "UniversityDB" database, create the following tables with appropriate attributes:
Table 1: "Students"
Attributes: student_id (Primary Key), first_name, last_name, date_of_birth, major

Table 2: "Courses"
Attributes: course_id (Primary Key), course_name, department, credit_hours

Table 3: "Enrollments"
Attributes: enrollment_id (Primary Key), student_id (Foreign Key referencing Students), course_id (Foreign Key referencing Courses), enrollment_date

3. Alter Tables and Columns:

Modify the "Students" table by adding a new column named "email" to store the email address of each student.

Modify the "Courses" table by altering the "credit_hours" column to be of type INTEGER.

4. Drop Datatype, Columns, and Tables:

Drop the "date_of_birth" column from the "Students" table.
Drop the "Enrollments" table from the "UniversityDB" database.
Drop the "UniversityDB" database.


