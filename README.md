# 📦 Smart Inventory Management System

A modern web-based Inventory Management System developed using **Node.js, Express.js, SQLite, HTML, CSS, JavaScript, and Tailwind CSS**. This application helps businesses manage products, suppliers, purchases, sales, inventory tracking, billing, and reporting from a single platform.

---

# 👨‍💻 Developer

**Ayush Agrahari**

GitHub Repository:
https://github.com/ayush17-agrahari/Smart-Inventory-Management-System

---

# 📖 Project Overview

The Smart Inventory Management System is designed to simplify inventory operations for small and medium-sized businesses. It provides an easy-to-use interface for managing stock, suppliers, purchases, sales, and reports.

The system automatically updates inventory quantities whenever a purchase or sale is recorded, reducing manual work and improving accuracy.

---

# 🎯 Objectives

* Manage products efficiently
* Maintain supplier information
* Record purchases and sales
* Track inventory automatically
* Generate invoices and bills
* Produce useful business reports
* Reduce manual inventory errors
* Improve stock visibility

---

# ✨ Features

## 🔐 User Authentication

* Secure login system
* User registration
* Session management
* Protected routes

## 📦 Product Management

* Add new products
* Update product details
* Delete products
* Search products
* Manage product stock
* Product price management

## 👥 Supplier Management

* Add suppliers
* Edit supplier information
* Delete suppliers
* Store contact details
* Track supplier records

## 🛒 Purchase Management

* Create purchase entries
* Select supplier
* Add multiple products
* Automatic inventory increase
* Purchase history tracking

## 💰 Sales & Billing

* Customer details management
* Invoice generation
* GST calculation
* Discount calculation
* QR Code generation
* PDF invoice download
* Automatic inventory reduction

## 📊 Reports & Analytics

* Sales reports
* Purchase reports
* Inventory reports
* Stock tracking
* Business insights

## 📱 Responsive Design

* Desktop support
* Tablet support
* Mobile support
* Modern user interface

---

# 🏗️ System Architecture

Frontend:

* HTML5
* CSS3
* Tailwind CSS
* JavaScript

Backend:

* Node.js
* Express.js

Database:

* SQLite3

Tools:

* Git
* GitHub
* VS Code
* Render

---

# 📁 Project Structure

```text
Smart-Inventory-Management-System
│
├── database
│   └── inventory.db
│
├── routes
│   ├── auth.js
│   ├── products.js
│   ├── suppliers.js
│   ├── purchases.js
│   ├── sales.js
│   ├── reports.js
│   └── shorten.js
│
├── utils
│   └── api.js
│
├── index.html
├── login.html
├── register.html
├── products.html
├── suppliers.html
├── purchases.html
├── sales.html
├── reports.html
├── settings.html
│
├── server.js
├── package.json
├── package-lock.json
├── README.md
└── .env
```

---

# ⚙️ Installation Guide

## Step 1: Clone Repository

```bash
git clone https://github.com/ayush17-agrahari/Smart-Inventory-Management-System.git
```

## Step 2: Open Project

```bash
cd Smart-Inventory-Management-System
```

## Step 3: Install Dependencies

```bash
npm install
```

## Step 4: Start Server

```bash
npm start
```

or

```bash
node server.js
```

## Step 5: Open Application

```text
http://localhost:5000
```

---

# 💾 Database Tables

The system uses SQLite Database.

## Products

Stores:

* Product Name
* Price
* Quantity
* Category
* Description

## Suppliers

Stores:

* Supplier Name
* Contact Person
* Phone Number
* Email
* Address

## Purchases

Stores:

* Supplier Details
* Purchase Date
* Purchase Amount
* Purchase Items

## Sales

Stores:

* Invoice Number
* Customer Information
* Products Sold
* GST
* Grand Total

---

# 🔄 Inventory Workflow

### Purchase Process

Supplier → Purchase Entry → Database Update → Stock Increase

### Sales Process

Customer Purchase → Invoice Generation → Database Update → Stock Decrease

---

# 📊 Future Enhancements

* Barcode Scanner
* Email Invoices
* SMS Notifications
* Cloud Database
* Multi-user Access
* Role-Based Authentication
* AI-Based Stock Prediction
* Advanced Dashboard Analytics

---

# 🚀 Deployment

The project can be deployed on:

* Render
* Railway
* Vercel
* AWS
* Azure

---

# 🛠 Technologies Used

| Technology   | Purpose            |
| ------------ | ------------------ |
| Node.js      | Backend Runtime    |
| Express.js   | Web Framework      |
| SQLite       | Database           |
| HTML5        | Frontend Structure |
| CSS3         | Styling            |
| Tailwind CSS | Responsive UI      |
| JavaScript   | Client-side Logic  |
| Git          | Version Control    |
| GitHub       | Repository Hosting |

---

# 🎓 Academic Relevance

This project is suitable for:

* B.Tech Final Year Projects
* MCA Projects
* BCA Projects
* Inventory Management Research
* Full Stack Development Learning

---

# 📄 License

This project is developed for educational and learning purposes.

---

# ⭐ Author

### Ayush Agrahari

GitHub:
https://github.com/ayush17-agrahari

Project:
https://github.com/ayush17-agrahari/Smart-Inventory-Management-System

If you find this project useful, consider giving it a ⭐ on GitHub.
