# 📚 Bookstore — Full-Stack Web Application

A full-stack **online bookstore web application** developed as part of our **Bachelor's Graduation Project in Computer Science**.

The application provides a complete online bookstore experience, allowing users to browse and search for books, manage their accounts, save books, add items to a shopping cart, place orders, and interact with an administration dashboard.

---

## 👥 Project Team

This project was collaboratively developed by:

* **Abdelmoukit Abed**
* **Bachir Zekhnine**
* **Youcef Abed**

The project was developed as our **Bachelor's Graduation Project**, with the team contributing to different aspects of the application's design, development, database, testing, and integration.

---

## 🎓 Academic Project

**Project Type:** Bachelor's Graduation Project
**Field:** Computer Science
**Application Type:** Full-Stack Web Application
**Team Size:** 3 Developers

---

## 🚀 Overview

The Bookstore application was designed to simulate a complete online bookstore platform.

The system consists of a customer-facing web application and an administrative interface, supported by a PHP backend and a MySQL relational database.

The main goal of the project was to apply software development concepts learned during our university studies to the design and implementation of a complete real-world web application.

---

## ✨ Features

### 👤 User Management

* User registration
* User login and authentication
* User authorization
* Account management
* Session management

### 📚 Book Management

* Browse available books
* Search for books
* View book information
* Save/like books
* Manage book-related data

### 🛒 Shopping & Orders

* Add books to the shopping cart
* Manage cart items
* Place orders
* Manage order information
* Track user orders

### 🛠️ Administration

* Dedicated administration dashboard
* Inventory management
* Book management
* User and application data management
* Administrative operations

### 🗄️ Database

* Relational MySQL database
* Structured database schema
* SQL scripts for database creation
* Database diagrams
* Backend database integration

---

## 🛠️ Technologies Used

| Technology     | Purpose                                    |
| -------------- | ------------------------------------------ |
| **PHP**        | Backend and server-side application logic  |
| **MySQL**      | Relational database management             |
| **HTML5**      | Application structure                      |
| **CSS3**       | User interface and styling                 |
| **JavaScript** | Client-side functionality and interactions |
| **Apache**     | Web server                                 |
| **XAMPP**      | Local development environment              |
| **Composer**   | PHP dependency management                  |
| **SQL**        | Database design and queries                |

---

## 🏗️ Project Structure

```text
Bookstore/
│
├── Pages/              # Application pages
├── Scripts/            # Application scripts
├── admin/              # Administration dashboard
├── api/                # API functionality
├── config/             # Configuration files
├── css/                # Stylesheets
├── database/           # Database resources
├── diagrams/           # System and database diagrams
├── images/             # Application images
├── inc/                # Included components
├── includes/           # Reusable PHP components
├── js/                 # JavaScript files
├── models/             # Data and database models
├── services/           # Application services
├── sql/                # SQL scripts
├── utils/              # Utility functions
│
├── api.php             # API entry point
├── connection.php      # Database connection
├── db_tables.sql       # Database table definitions
├── index.php           # Main application entry point
├── composer.json       # PHP dependencies
├── composer.lock       # Locked dependency versions
└── bookstore_schema.pdf # Database schema documentation
```

---

## 👨‍💻 My Contribution

This repository is **my personal fork of the original team project**.

The application was developed collaboratively by the three team members. My work on the project included contributing to the development and integration of different parts of the application, including frontend, backend, database-related functionality, debugging, and testing.

### My contribution included:

* Contributing to frontend development
* Contributing to backend development using PHP
* Working with the MySQL database
* Implementing and integrating application functionality
* Debugging and testing the application
* Working on the integration of different components
* Participating in the design and development of the overall system

> **Note:** The project was developed collaboratively. The original repository and Git history are preserved to properly attribute the work of all team members.

---

## 🗄️ Database Design

The application uses **MySQL** as its relational database system.

Database-related resources included in the project include:

```text
database/
sql/
db_tables.sql
bookstore_schema.pdf
```

The database design supports the main entities and operations required by the bookstore, including users, books, orders, and related application data.

---

## 📐 System Design

The project includes design documentation and diagrams used during the development process.

These resources can be found in:

```text
diagrams/
bookstore_schema.pdf
```

They document the structure and relationships of the application's different components and database entities.

---

## ⚙️ Installation

### 1. Install XAMPP

Install **XAMPP** with Apache, MySQL, PHP, and phpMyAdmin.

### 2. Clone the repository

Clone the repository into your XAMPP `htdocs` directory:

```bash
git clone https://github.com/mo9it2003/Bookstore.git
```

For example:

```text
C:/xampp/htdocs/Bookstore
```

### 3. Start XAMPP

Open the XAMPP Control Panel and start:

* Apache
* MySQL

### 4. Create the database

Open phpMyAdmin and create a database named:

```text
bookstore
```

Import the provided SQL file:

```text
db_tables.sql
```

### 5. Configure the database connection

Configure the database connection according to your local XAMPP environment.

A typical configuration is:

```php
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "bookstore";
```

### 6. Run the application

Open your browser and navigate to:

```text
http://localhost/Bookstore/
```

---

## 🖥️ Application Workflow

The general application workflow is:

```text
User
 │
 ├── Register / Login
 │
 ├── Browse Books
 │      │
 │      ├── Search
 │      └── View Book Details
 │
 ├── Like / Save Books
 │
 ├── Add Books to Cart
 │
 └── Place Order
        │
        ▼
     Database


Administrator
 │
 └── Admin Dashboard
        │
        ├── Manage Books
        ├── Manage Inventory
        └── Manage Application Data
```

---

## 📸 Screenshots

Screenshots can be added here to showcase the main parts of the application.

Recommended screenshots:

```text
screenshots/
│
├── homepage.png
├── books.png
├── book-details.png
├── login.png
├── register.png
├── liked-books.png
├── cart.png
├── orders.png
└── admin-dashboard.png
```

---

## 🎯 What We Learned

Developing this project gave us practical experience with:

* Full-stack web development
* PHP backend development
* MySQL database design
* SQL queries
* HTML and CSS
* JavaScript
* User authentication and authorization
* API development and integration
* Database connectivity
* Software architecture
* System and database modeling
* Debugging and testing
* Git and GitHub
* Collaborative software development

---

## 📚 Project Context

This application was developed as part of our university **Bachelor's Graduation Project**.

The project allowed us to take a software idea from the design stage through implementation and testing, while working collaboratively as a development team.

It represents practical experience in building and integrating a complete web application rather than a collection of isolated programming exercises.

---

## 🔗 Original Repository

This repository is a fork of the original project repository:

**Original Repository:**
https://github.com/kkbbmrl/Bookstore

The original repository and its Git history are preserved for proper project attribution.

This repository serves as **Abdelmoukit Abed's personal copy of the project**, allowing the project to be presented and maintained as part of his personal GitHub portfolio.

---

## 👥 Team

### Abdelmoukit Abed

Computer Science — Full-Stack Web Development

### Bachir Zekhnine

Computer Science — Full-Stack Web Development

### Youcef Abed

Computer Science — Full-Stack Web Development

---

## 📄 License

This project is licensed under the MIT License.

See the `LICENSE` file for more information.

---

## ⭐ About the Project

**Bookstore** is a university graduation project demonstrating practical experience in designing and developing a complete **PHP + MySQL full-stack web application**, including user authentication, book management, shopping cart functionality, order processing, database integration, and an administrative dashboard.

Built collaboratively by **Abdelmoukit Abed, Bachir Zekhnine, and Youcef Abed**.
