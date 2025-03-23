# 📚 Library Management System

This project is a **Library Management System** developed using **PHP** and **MySQL**, designed for managing books, students, and book issuance in a digital library environment. It provides user-friendly dashboards for both **Admins** and **Students**.

---

## ✅ Features

- 🔐 Secure login for Admins and Students
- 📚 Add, Delete, and Manage Books
- 👥 Add and Manage Student Profiles
- 📦 Book Requests and Approvals
- 🧾 Book Issue and Return Tracking
- 📊 Detailed Reports for Admins
- 📁 Photo Upload for Book Covers
- 🏷️ Department-based Book Categorization (IT, Civil, EC, Electrical)

---

## 🖼️ UI Snapshots

### 🟢 Admin Dashboard – Add New Book
![Admin Panel](sandbox:/mnt/data/stepcount.png)

### 🔵 Login Interface – Admin & Student
![Login Panel](sandbox:/mnt/data/app.PNG)

### 📢 Project Highlights Banner
![Library Banner](sandbox:/mnt/data/abc.PNG)

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS
- **Backend**: PHP
- **Database**: MySQL
- **Assets**: PNG/JPG Icons & Visuals

---

## 🗃️ Key Files

```
.
├── index.php                        # Main login page
├── addpersonserver_page.php        # Adds student/person details
├── addbookserver_page.php          # Adds new book entries
├── login_server_page.php           # Student login backend
├── loginadmin_server_page.php      # Admin login backend
├── admin_service_dashboard.php     # Admin operations
├── approvebookrequest.php          # Book approval logic
├── issuebook_server.php            # Book issuing handler
├── deletebook_dashboard.php        # Admin book deletion
├── deleteuser.php                  # Admin user deletion
├── data_class.php                  # Backend class for DB queries
├── db.php                          # Database connection
├── library_managment.sql           # SQL file to import DB schema
└── README.md                       # Project documentation
```

---

## 🧾 Login Credentials (Default)

| Role    | Email              | Password   |
|---------|--------------------|------------|
| Admin   | admin@library.com  | admin123   |
| Student | student@library.com| student123 |

> You can update these in the MySQL database after import.

---

## 🙌 Acknowledgments

- UI/UX inspirations from open-source PHP dashboard templates.
- Developed by **Bhuvi Mangwani**.
