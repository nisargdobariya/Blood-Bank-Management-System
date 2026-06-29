# 🩸 Blood Bank Management System

A comprehensive **Blood Bank Management System** developed using **PHP, MySQL, HTML, CSS, and JavaScript**. The system digitizes blood bank operations by providing role-based access for **Administrators, Employees, and Donors**, allowing efficient management of blood donations, inventory, appointments, and user information.

---

# 📌 Project Overview

The Blood Bank Management System is a web-based application designed to simplify and automate blood bank operations.

The system enables:

* Blood donor registration
* Blood inventory management
* Appointment scheduling
* Blood request management
* Employee management
* Secure authentication
* Role-based access control

The objective of this project is to reduce manual work, improve data accuracy, and provide an efficient platform for managing blood bank activities.

---

# 🚀 Features

## 👨‍💼 Admin Module

* Admin Login
* Dashboard
* Add Employee
* Edit Employee
* Delete Employee
* Add Donor
* Edit Donor
* Delete Donor
* View Reports
* Blood Inventory Monitoring
* Manage System Data

---

## 👨‍⚕️ Employee Module

* Employee Login
* Dashboard
* Manage Donors
* Add Blood Inventory
* Manage Blood Requests
* Appointment Management
* Update Appointment Status
* Generate Reports

---

## 🩸 Donor Module

* Donor Registration
* Secure Login
* Profile Management
* Book Donation Appointment
* View Notifications
* Manage Appointments
* Update Personal Information

---

## 🔐 Authentication System

* User Login
* User Registration
* Forgot Password
* OTP Verification
* Password Reset
* Secure Session Handling

---

## 📊 Database Management

* Donor Records
* Employee Records
* Blood Inventory
* Blood Requests
* Appointment Records
* User Authentication

---

# 🏗 Project Architecture

```text
                User
                  │
      ┌───────────┼────────────┐
      │           │            │
      ▼           ▼            ▼
   Admin      Employee      Donor
      │           │            │
      └───────────┼────────────┘
                  │
             PHP Backend
                  │
              MySQL Database
```

---

# 📂 Project Structure

```text
Blood-Bank-Management-System
│
├── Admin/
│   ├── Dashboard
│   ├── Employee Management
│   ├── Donor Management
│   ├── Reports
│
├── Employee/
│   ├── Dashboard
│   ├── Blood Inventory
│   ├── Blood Requests
│   ├── Appointment Management
│
├── Donor/
│   ├── Dashboard
│   ├── Appointment Booking
│   ├── Profile
│   ├── Notifications
│
├── Login/
│   ├── Login
│   ├── Registration
│   ├── OTP Verification
│   ├── Forgot Password
│
├── Database/
│   └── blood_db.sql
│
├── CSS/
├── index.html
└── README.md
```

---

# 💻 Technology Stack

| Category | Technology              |
| -------- | ----------------------- |
| Frontend | HTML5, CSS3, JavaScript |
| Backend  | PHP                     |
| Database | MySQL                   |
| Server   | Apache (XAMPP / WAMP)   |

---

# ⚙️ Installation Guide

## Prerequisites

* PHP 8.x or later
* MySQL
* Apache Server
* XAMPP / WAMP / LAMP

---

## Step 1

Clone the repository

```bash
git clone https://github.com/yourusername/Blood-Bank-Management-System.git
```

---

## Step 2

Move the project folder to your web server.

Example:

```text
xampp/htdocs/
```

---

## Step 3

Create a database

```
blood_db
```

---

## Step 4

Import

```
Database/blood_db.sql
```

using phpMyAdmin.

---

## Step 5

Update database credentials inside the project's PHP connection files if required.

Example:

```php
$host = "localhost";
$user = "root";
$password = "";
$database = "blood_db";
```

---

## Step 6

Start

* Apache
* MySQL

---

## Step 7

Open

```
http://localhost/Blood-Bank-Management-System/
```

---

# 🔄 System Workflow

```text
User
   │
   ▼
Login / Register
   │
   ▼
Role Authentication
   │
   ├──────────────┐
   ▼              ▼
Admin        Employee
   │              │
   └──────┬───────┘
          ▼
     MySQL Database
          ▲
          │
       Donor Portal
```

---

# 📈 Key Functionalities

* Blood Donation Management
* Blood Inventory Tracking
* Appointment Scheduling
* Employee Management
* Donor Management
* User Authentication
* Password Recovery
* Notifications
* Report Generation

---

# 🔒 Security Features

* Role-Based Access Control
* Session Management
* Authentication System
* Password Reset using OTP
* Database Connectivity through PHP

---

# 📷 Screenshots

Add screenshots here.

Example:

```text
Landing Page

Admin Dashboard

Employee Dashboard

Donor Dashboard

Appointment Module

Blood Inventory
```

---

# 🎯 Future Enhancements

* Email Notifications
* SMS Notifications
* Blood Availability Prediction
* Analytics Dashboard
* REST API
* Docker Deployment
* QR Code Based Donor Identification
* Responsive Mobile Design
* JWT Authentication
* Cloud Deployment

---

# 👨‍💻 Author

**Nisarg Dobariya**

Bachelor of Technology (Computer Engineering)

Cybersecurity | Web Development | DevOps | Cloud Computing

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourprofile

---

# 📄 License

This project is developed for educational and academic purposes.

Feel free to modify and enhance it for learning and research.
