Library Management System in Python
Overview
This repository contains a simple Library Management System implemented in Python. The system allows users (students) to interact with a library, enabling them to view available books, borrow books, and return books. This project demonstrates fundamental programming concepts such as classes, methods, user input, and control flow.
Features
•	Library Class: Manages the list of available books, handles borrowing and returning of books, and displays current book availability.
•	Student Class: Allows students to request books for borrowing and to return borrowed books.
•	Interactive Menu: Provides a user-friendly interface where students can choose options to list books, request a book, return a book, or exit the program.
Usage
1.	Run the Program: Execute the script to start the library management system.
2.	Choose an Option: Follow the prompts in the interactive menu to list available books, borrow a book, or return a book.
3.	Enjoy Reading: Students can borrow books for a duration of 30 days and are encouraged to return them promptly.
Code Structure
•	Library Class:
o	__init__: Initializes the library with a list of books.
o	displayAvailableBooks: Displays all books currently in the library.
o	borrowBook: Allows students to borrow a book if available.
o	returnBook: Accepts a returned book and adds it back to the library.
•	Student Class:
o	requestBook: Prompts the user for the name of a book they wish to borrow.
o	returnBook: Prompts the user for the name of a book they wish to return.
Future Enhancements
•	Database Integration: Implement a database to store book records and student transactions.
•	User Authentication: Add login functionality for students to manage their accounts.
•	Enhanced User Interface: Develop a graphical user interface (GUI) for improved usability.
This project is a great way to learn about basic object-oriented programming concepts and can be extended to include more advanced features as needed. Feel free to explore, modify, and contribute

