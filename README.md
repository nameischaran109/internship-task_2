SQL Developer Internship - Task 2

 Data Insertion and Handling Nulls

 Objective

The objective of this task was to practice Data Manipulation Language (DML) operations such as inserting, updating, and deleting records while handling NULL values in a database.

 Domain Chosen

Library Management System

### Tools Used

* DB Fiddle
* GitHub

### Project

Library Management System

### DB Fiddle Link

https://www.db-fiddle.com/f/njjEoP4prJdAoSq3oNXwCj/1

### Database Tables

#### Authors

* author_id (Primary Key)
* author_name

#### Books

* book_id (Primary Key)
* title
* isbn
* publication_year
* author_id (Foreign Key)

#### Members

* member_id (Primary Key)
* member_name
* email

#### Borrowings

* borrow_id (Primary Key)
* member_id (Foreign Key)
* book_id (Foreign Key)
* borrow_date
* return_date

### Operations Performed

#### INSERT Statements

Inserted sample records into:

* Authors
* Books
* Members
* Borrowings

#### NULL Handling

Used NULL values for:

* Missing ISBN information
* Missing Email information
* Missing Return Date information

#### UPDATE Statements

Updated:

* Member email address
* Book publication year

#### DELETE Statements

Deleted a borrowing record using a WHERE condition.

#### SELECT Statements

Retrieved records from all tables to verify the changes made through DML operations.

### Dataset

A sample dataset was created using INSERT statements to demonstrate data insertion, updates, deletions, and NULL value handling.

### Files Included

* task2_dml.sql
* README.md

### Key Concepts Covered

* DML (Data Manipulation Language)
* INSERT INTO
* UPDATE
* DELETE
* NULL Handling
* WHERE Clause
* Foreign Keys

### Outcome

Successfully performed INSERT, UPDATE, DELETE, and SELECT operations on a Library Management System database while handling NULL values and maintaining data consistency.
