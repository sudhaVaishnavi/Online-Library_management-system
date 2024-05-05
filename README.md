Online Library Management System

This project is a simple online tool for managing a library's books, borrowers, and loans. It's built using MySQL for the database and SQL for various functions.

What It Does?
1. Book Management: Keeps track of books, their publishers, and authors.
2. Branch Management: Manages library branches, including their names and addresses.
3. Borrower Management: Records borrower details like name, address, and contact.
4. Loan Management: Tracks who borrowed which book, from which branch, and when.

How It Works?
1. Database Setup: Run the SQL script to set up the database and insert sample data.
2. Use Stored Procedures: Execute the provided stored procedures for different tasks.
   - Check how many copies of a book are available at a specific branch.
   - See the total number of copies of a book across all branches.
   - Find borrowers who haven't borrowed any books.
   - Get info on borrowers with books due on a certain date.
   - See the total number of loans per branch.
   - Find borrowers who've borrowed more than five books.
3. Customize Modify or extend the stored procedures for your specific needs.

How to Use?

1. Set Up Database: Create the db_LibraryManagement database and execute the provided SQL code.
2. Run Procedures: Execute the stored procedures using your preferred MySQL client.
3. Customize: Adjust the procedures or add new ones according to your requirements.

