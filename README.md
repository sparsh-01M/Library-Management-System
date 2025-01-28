Library Management System (SQL Stored Procedures)
I developed a Library Management System using SQL, which includes creating and managing a database and tables to track books, publishers, library branches, borrowers, and book loans. The system also includes stored procedures for managing and querying data in the database.

Key components of the project:

Database Setup:

Created a database to store information about books, publishers, borrowers, and library branches.
Tables Created:

Publishers: Stores details about publishers (name, address, phone number).
Books: Stores information about books (title, publisher).
Library Branches: Stores information about library branches (name, address).
Borrowers: Stores information about library borrowers (name, address, phone).
Book Loans: Tracks the books borrowed by borrowers, including loan date and due date.
Book Copies: Keeps track of the number of copies of each book available in the library branches.
Book Authors: Links books to their authors.
Data Insertion: Populated the tables with sample data for publishers, books, borrowers, and library branches.

Stored Procedures:

Created stored procedures for various tasks:
Checking the number of copies of a book in a specific library branch.
Checking how many copies of a book are available across all branches.
Finding borrowers who have no books checked out.
Retrieving information about books that are due today for a specific branch.
Skills Applied:
SQL Database Design (creating tables, defining relationships, primary/foreign keys)
Data Management (inserting sample data)
Stored Procedure Development (creating reusable queries to interact with the database)
