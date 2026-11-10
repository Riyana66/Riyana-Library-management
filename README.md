Library Management System
A beginner-friendly MySQL database project for managing books, students, and book issue/return records.

Files in this repository

ERD.png – Entity Relationship Diagram.
README.md – Project description and setup instructions.
library_management.sql – Creates the database and tables.
sample_data.sql – Inserts example records and demonstrates a book issue.

Requirements
MySQL Server
MySQL Workbench or another MySQL client

How to run
Open MySQL Workbench.
Open and execute library_management.sql first.
Open and execute sample_data.sql next.
Run USE LibraryManagement; and then SELECT * FROM Books; to view the books.


Main tables
Books: stores book details and available quantity.
Students: stores student details.
Issues: records which student borrowed which book, including issue, due, and return dates.
