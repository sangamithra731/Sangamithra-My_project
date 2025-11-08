📚 Library Management System – Python Project (Creative Overview)

Welcome to a mini-library that lives inside your computer! This Python-based Library Management System is a simple yet smart CLI project that brings the real-world library experience into code. It supports two user roles—👩‍🏫 Librarians and 🎓 Students—each with their own powers and menus.

Built using core Python and CSV files (no heavy databases!), the system neatly manages books, users, borrow records, and fines. Passwords are handled securely using the pwinput module 🔒.


---

🛠 Modules Used

📄 csv – Stores books and users like a lightweight database

⏰ datetime – Tracks borrow dates, due dates, and fines

🗂 os – Handles file creation and directory work

🔐 pwinput – Lets users enter passwords securely



---

👩‍🏫 Librarian Features

Librarians act as the managers of this digital library. Once logged in, they can:

➕ Add new books

📘 View entire book list

✏️ Update book info or quantity

❌ Remove books

✅ Register and login safely


They control the heart of the system!


---

🎓 Student Features

Students are the readers and borrowers. After registration and login, they can:

📚 View all available books

📥 Borrow books and receive a due date

📤 Return books and check for late fines

🗑 De-register if they want to leave the system


A smooth and simple borrowing journey!


---

⚙️ How the System Works

When you run main.py, users choose whether they’re a Librarian 👩‍🏫 or a Student 🎓.
Each role opens a customized menu:

✅ Register

✅ Login

✅ Perform their special actions


All operations—borrowing, updating, returning—are stored through CSV files, making the system lightweight and beginner-friendly.

