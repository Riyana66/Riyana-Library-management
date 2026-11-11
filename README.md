7. Project Questions
The project consists of 15 questions divided into four phases.

Phase 1 - Database Basics

C1: Draw the Entity Relationship Diagram.
C2: Find the total number of members, books and issue records.
Phase 2 - SQL Queries

C3: Find the number of titles and available copies in each category.
C4: Find the top 5 most borrowed books.
C5: Identify members who have never borrowed a book.
C6: Display currently issued books with member names and due dates.
C7: Find late returns and calculate their fines.
C8: Calculate the total fine for each member.
C9: Compare borrowing activities between students and faculty.
C10: Rank members according to the number of books borrowed.
C11: Identify the most popular book category.
C12: Find books with zero available copies and pending issues.
Phase 3 - Database Automation

C13: Create a stored procedure to display a member's borrowing history.
C14: Create a trigger to automatically reduce available copies when a new issue is inserted.
Phase 4 - Conclusion

C15: Suggest improvements to library management based on the query results.
8. Files Included
File	Description
schema.sql	Creates the database and tables.
insert_data.sql	Inserts sample records into the database.
queries.sql	Contains SQL queries for C2 to C14.
notes.md	Contains query summaries and conclusions.
erd.jpg	Entity Relationship Diagram.
9. How to Run the Project
Open MySQL Workbench.
Execute schema.sql to create the database and tables.
Execute insert_data.sql to insert the sample records.
Select the librarydb database.
Execute the queries from queries.sql .
Check the output for each question.
To verify the records, run:

--> sql USE librarydb;

SELECT COUNT() FROM members; SELECT COUNT() FROM books; SELECT COUNT(*) FROM issues;

Expected output:

Members: 12
Books: 15
Issues: 32
10. Learning Outcomes
Through this project, I learned how to create and manage relational databases using MySQL.

I gained practical knowledge of SQL queries, joins, aggregate functions, subqueries and window functions. I also learned how stored procedures and triggers can be used to automate database operations.

This project helped me understand how database concepts can be applied to a real-world library management system.

11. Conclusion
The Library Management System demonstrates how MySQL can be used to maintain and analyse library records. The queries help identify popular books, members with pending returns and late return fines.

Overall, this mini project helped me improve my practical understanding of database management and SQL.
