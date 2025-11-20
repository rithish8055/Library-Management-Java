# LibraryManagementSystem_JAVA

The Library Management System project demonstrates the application of Object-Oriented Programming (OOP) concepts and CRUD (Create, Read, Update, Delete) operations in Java. The system allows users to manage a collection of books in a library through a console-based interface.

OOP Concepts Applied:
Encapsulation:

Book Class: Encapsulates the details of a book with private attributes and public getter and setter methods.
Library Class: Manages a collection of Book objects and provides methods to manipulate this collection.
Inheritance (Optional for this example, but can be extended):

You could introduce a base class like LibraryItem if you plan to manage different types of items (e.g., books, magazines) with shared properties and behaviors.
Polymorphism (Optional for this example, but can be extended):

By defining methods in interfaces or abstract classes, you could create multiple implementations that handle different types of library items.
Abstraction:

You abstract the details of book management within the Library class and provide a simple interface for interaction through methods like addBook, removeBook, updateBook, and listBooks.
CRUD Operations Applied:
Create:

addBook(Book book): Adds a new book to the library collection.
Read:

listBooks(): Displays the list of all books currently in the library.
Update:

updateBook(String isbn, Book updatedBook): Updates the details of an existing book based on its ISBN.
Delete:

removeBook(String isbn): Removes a book from the library collection by its ISBN.
