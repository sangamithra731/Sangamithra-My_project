#**Library Management System – Python Project Explanation**

This project is a simple **Library Management System** built using the **Python programming language**. It is a **command-line interface (CLI)** application designed to simulate the operations of a real-world library. The system supports two types of users: **Librarians** and **Students**, each having different sets of functionalities.

The main purpose of the project is to manage library books and user interactions such as borrowing and returning books. The system uses Python's built-in file handling to store and retrieve data using **CSV files**, so no external database is required. An external module called **pwinput** is used to securely take password input from users.

---

### Modules Used:

* `csv` – for storing and reading user and book data.
* `datetime` – for tracking book borrow dates and fines.
* `os` – for handling file and directory operations.
* `pwinput` – for secure password input (requires installation).

---

### Librarian Features:

* Register and login to the system.
* Add new books to the library.
* View the list of all books.
* Update book information (e.g., quantity or details).
* Remove books from the system.

---

### Student Features:

* Register and login to their own account.
* View all available books in the library.
* Borrow books and get a due date.
* Return books and check for late fines.
* Option to de-register (delete account).

---

### How it Works:

After starting the program (`main.py`), users can choose whether they are a librarian or student. Depending on their choice, they are taken to a menu with their respective options. All actions such as registering, logging in, viewing or updating data are handled through user input and saved using CSV files.
