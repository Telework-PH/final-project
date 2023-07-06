# Final Project

**Project Name:** Library Management System

**Objective:** To design and implement a comprehensive system in C++ for managing a library.

**Project Description:**

The Library Management System is a project that allows students to implement and showcase their C++ programming skills. This system should provide an interface for librarians to manage library books and patrons, track check-outs and returns, and facilitate fines for late returns.

The system should be able to perform the following functions:

1. **Manage Books:**
    - Add a new book: This feature allows the user to add a new book with details like book ID, title, author, publisher, and availability status.
    - Search for a book: This feature allows the user to search for a book by book ID, title, or author.
    - Update a book: This feature allows the user to update the details of an existing book.
    - Delete a book: This feature allows the user to delete an existing book from the system.
    - Display all books: This feature allows the user to view all the books in the system.

2. **Manage Patrons:**
    - Add a new patron: This feature allows the user to add a new patron with details like patron ID, name, and contact details.
    - Search for a patron: This feature allows the user to search for a patron by patron ID or name.
    - Update a patron: This feature allows the user to update the details of an existing patron.
    - Delete a patron: This feature allows the user to delete an existing patron from the system.
    - Display all patrons: This feature allows the user to view all the patrons in the system.

3. **Manage Check-outs and Returns:**
    - Check-out a book: This feature allows the user to check-out a book for a patron. It should ask for the patron ID and the book ID and change the availability status of the book.
    - Return a book: This feature allows the user to return a checked-out book. It should ask for the patron ID and the book ID and update the availability status of the book. If the book is returned late, it should calculate and display the fine.
    - Display all check-outs: This feature allows the user to view all the check-outs in the system.

**Project Components:**

1. **Book, Patron, and CheckOut Classes:** These are the primary classes in the project. Each class should include member variables for its details and member functions to manage these details.

2. **File Handling:** The project should use file handling to store records. This means the system should be able to store the records even if it is closed and reopened.

3. **Input Validation:** The project should include sufficient input validation to prevent incorrect data entry.

4. **User Interface:** The project should have a text-based user interface that provides options to the user to manage books, patrons, and check-outs.

**Condition Handling:**

1. **Duplicate IDs:** When adding a new book or patron, check if a book or patron with the same ID already exists. If so, print a message saying "A book/patron with this ID already exists".

2. **Invalid IDs:** When checking out or returning a book, check if the book ID and the patron ID entered by the user exist in the system. If not, print a message saying "Invalid book/patron ID".

3. **Availability of Books:** Also, when checking out a book, check if the book is available. If not, print a message saying "The book is currently not available".

4. **Fines for Late Returns:** When returning a book, check if the book is returned within the due date. If not, calculate and display the fine.

5. **Error Handling:** When opening a

file for reading or writing, check if the file was opened successfully. If not, print an error message.

6. **Entity Not Found:** When searching for a book or patron, check if the book or patron was found. If not, print a message saying "Book/patron not found".

7. **Entity Existence:** When deleting a book or patron, check if the book or patron exists. If not, print a message saying "Book/patron does not exist".

8. **Edge Cases:** When displaying all books or patrons, check if the list of books or patrons is empty. If so, print a message saying "No books/patrons found".

**Extra Challenges:**

1. **Sort Records:** Add the ability to sort records based on different parameters, such as book title, patron name, checkout date, etc.
2. **Password-protected Access:** Make your program secure by adding password-protected access to the system.
3. **Exception Handling:** Ensure your code robustly handles potential errors and exceptions.

```
Note: For creating your project by partner,
1. Create a GitHub repository under Telework PH Group
2. Add me as a collaborator in your GitHub repository.
3. In the readme file, add your names.
```

