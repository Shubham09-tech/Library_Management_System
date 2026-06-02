# Library_Management_System

**Project Overview**

The Library Management System is a console-based application developed in Java that helps manage library operations efficiently. The system allows librarians (admins) to manage book records and enables students to issue and return books through a secure login process.

The project is designed to automate common library tasks such as book management, student verification, book issuance, return tracking, and fine calculation for overdue books.

The main objectives of this project are:

    1- To maintain records of books available in the library.
    2- To provide separate functionalities for administrators and students.
    3- To allow students to issue and return books securely.
    4- To keep track of book availability and stock.
    5- To calculate fines for overdue book returns.
    6- To implement efficient book searching using a Binary Search Tree (BST).

**Features
Admin Module**
The librarian/admin must log in using predefined credentials.

After successful login, the admin can:

    Add new books to the library.
    Delete existing books.
    Update book details such as:
    Book Name
    Quantity Available
    View available books in the library.
    Maintain book records efficiently.

**Student Module**
Students can access the system using their valid University ID.

After successful verification, students can:

    Search for books.
    Issue available books.

**Book Issuing Rules**
    1- A student must have a valid University ID.
    2- A student can issue a maximum of 2 books at a time.

If a book is not found, the system displays:
Book is not available in the library.

If a book is out of stock, the system displays:

This book is currently unavailable. Please try after some days.\n
The issue date and time are recorded when a book is issued.\n
Students must return books before the due date.



**How to Run**

Step 1 - Clone the repository
Step 2 - Navigate to the project directory:
  **cd LibraryManagementSystem**

Step 3 - Compile the Java files:
  **javac *.java**  

Step 4 - Run the application:
  **java Main**

Check due dates and fines (if applicable).
