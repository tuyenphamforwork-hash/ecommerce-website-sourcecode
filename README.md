# E-Commerce Website Source Code

## Introduction

This repository contains the source code of an open-source e-commerce website used for a software testing and quality assurance project. The system includes both customer-side and admin-side functionalities, allowing the testing team to perform comprehensive manual and automated testing using Katalon Studio.

The website is developed using PHP, MySQL, HTML, CSS, Bootstrap, and JavaScript, and serves as the application under test for functional testing, UI testing, regression testing, and automation testing.

---

# Project Purpose

This project was created for educational and software testing purposes, including:

- Manual Testing
- Automation Testing with Katalon Studio
- Functional Testing
- Regression Testing
- Defect Reporting
- Test Case Design
- UI/UX Evaluation

---

# Technologies Used

- PHP — Backend server-side development
- MySQL / MariaDB — Database management
- HTML5 — Page structure
- CSS3 — Styling and layout
- Bootstrap — Responsive UI framework
- JavaScript — Client-side interactions

---

# Main Features

## Customer-Side Features

- User registration
- User login/logout
- Product browsing
- Product search
- Category filtering
- Product detail pages
- Shopping cart management
- Checkout process
- Order placement
- User profile management

## Admin-Side Features

- Admin authentication
- Product management
- Category management
- Order management
- Customer management
- Inventory management
- Dashboard overview

---

# Project Structure

```text
E-commerce/
│
├── admin/                 # Admin panel
├── assets/                # CSS, JS, images
├── database/              # SQL database files
├── includes/              # Shared PHP components
├── products/              # Product pages
├── uploads/               # Uploaded images/files
└── ...
```

---

# Installation Guide

## Prerequisites

Make sure the following software is installed on your system:

- WampServer
- PHP 7.0 or later
- MySQL / MariaDB
- Google Chrome browser

---

# Setup Instructions

## 1. Clone Repository

```bash
git clone https://github.com/your-username/ecommerce-website-sourcecode.git
```

Or download the repository as a ZIP file and extract it manually.

---

## 2. Move Project to WampServer Directory

Move the project folder into:

```text
C:/wamp64/www/E-commerce
```

---

## 3. Create Database

Open phpMyAdmin and create a database named:

```text
db_ecommerce
```

---

## 4. Import Database

Import the SQL file located in:

```text
/database/db_ecommerce.sql
```

using phpMyAdmin.

---

## 5. Configure Database Connection

Open the configuration file:

```text
/admin/includes/config.php
```

Update database credentials if necessary:

```php
localhost
root
password
db_ecommerce
```

---

## 6. Start WampServer

Start all WampServer services and ensure Apache and MySQL are running correctly.

---

## 7. Run the Website

Customer website:

```text
http://localhost/E-commerce
```

Admin panel:

```text
http://localhost/E-commerce/admin
```

---

# Default Admin Account

```text
Email: dev.shahfahad@gmail.com
Password: adminfahad
```

---

# Testing Repository

Automation testing scripts and Katalon Studio project files are maintained in a separate repository:

```text
ecommerce-website-testing
```

This separation helps keep the application source code independent from automation scripts, reports, and testing artifacts.

---

# Recommended Testing Environment

To avoid compatibility issues during automation testing, all team members should use:

- Same Katalon Studio version
- Same Google Chrome version
- Same ChromeDriver version

---

# Known Limitations

Current limitations of the project include:

- No online payment gateway integration
- Limited security validation
- No email notification system
- Basic input validation
- Minimal performance optimization

---

# Future Improvements

Possible future enhancements:

- Payment gateway integration
- Product review and rating system
- Wishlist functionality
- Advanced search and filtering
- Email notifications
- UI/UX improvements
- Security enhancements
- Mobile responsiveness optimization

---

# Credits

This project is based on and customized from the following open-source resources:

## Front-end Template

Repository:
codewithsadee/anon-ecommerce-website

## Admin Panel Template

Repository:
Bhabishya-123/E-commerce

Additional modifications, integrations, and testing implementations were developed for educational and software testing purposes.

---

# License

This project is intended for educational, learning, and software testing purposes only.
