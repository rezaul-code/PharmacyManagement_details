# 💊 Pharmacy Management System

## 📌 Project Overview

The **Pharmacy Management System** is a modern digital platform designed to simplify pharmacy operations and replace traditional manual registers.

It helps pharmacies efficiently manage:

* Medicine inventory
* Billing and invoice generation
* Stock monitoring
* Staff management
* Pharmacy configuration
* Sales analytics and business insights

The system is built using **Java, Spring Boot, HTML, CSS, JavaScript, and MySQL**, following a **clean MVC architecture** that ensures scalability and maintainability.

⚠️ **Important Notice**

This repository is a **public showcase repository** created to demonstrate the system features and workflow.

The **actual source code repository is private** to protect the intellectual property and original implementation.

If you are interested in using or purchasing this system, please contact the author.

---

# 🖥️ Application Interface

Below are some screenshots demonstrating the main modules and workflow of the system.

---

## 🏠 Home Page

<img src="screenshots/home-page.png" width="650">

The home page provides an introduction to the pharmacy system and allows users to navigate to login or registration pages.

---

## 🔐 Login System

<img src="screenshots/login.png" width="450">

The login system allows registered users to securely access the pharmacy system.

Features include:

* Secure authentication
* Session management
* Role-based access

---

## 📝 User Registration

<img src="screenshots/register.png" width="450">

New pharmacy users can create an account using the registration interface.

Once registered, users can log in and manage their pharmacy operations.

---

## 📊 Dashboard (Admin)

<img src="screenshots/dashboard-admin.png" width="700">

The admin dashboard provides a complete overview of the pharmacy system including:

* Total medicines
* Inventory overview
* Billing statistics
* Sales analytics
* System management tools

---

## 💊 Dashboard (Pharmacist)

<img src="screenshots/dashboard-pharmacist.png" width="700">

The pharmacist dashboard focuses on operational tasks such as:

* Medicine inventory
* Billing system
* Stock monitoring
* Daily sales activities

---

## 💊 Add Medicine

<img src="screenshots/add-medicine.png" width="700">

Pharmacy staff can add new medicines with details such as:

* Manufacturer
* Batch number
* Expiry date
* Purchase price
* Selling price
* GST percentage
* Available stock

The system automatically generates a **unique medicine code** for each medicine.

---

## 📦 Medicine Inventory

<img src="screenshots/inventory.png" width="700">

The inventory page shows all medicines stored in the pharmacy database.

Each medicine record includes:

* Medicine Code
* Medicine Name
* Manufacturer
* Batch Number
* Expiry Date
* Purchase Price
* Selling Price
* Profit Margin
* GST Percentage
* Available Stock

This helps staff monitor stock levels and medicine availability.

---

## 🧾 Billing System

<img src="screenshots/new-bill.png" width="700">

The billing module allows staff to quickly generate medicine bills.

Features include:

* Autocomplete medicine search
* Multiple medicines per bill
* Quantity-based billing
* Automatic GST calculation
* Real-time bill total
* Instant invoice generation

---

## 🧾 Invoice Generation

<img src="screenshots/invoice.png" width="700">

Once a bill is generated, the system creates a clean invoice containing:

* Pharmacy information
* Patient details
* Purchased medicines
* GST breakdown
* Grand total

---

## 🖨️ Printable Invoice

<img src="screenshots/invoice-print.png" width="700">

The invoice can be printed directly for customers.

The layout is optimized for **clear and professional billing records**.

---

# 📊 Sales Analytics

<img src="screenshots/sales-analytics.png" width="700">

The **Sales Analytics module** provides insights into pharmacy business performance.

Features include:

* Top selling medicines
* Revenue analytics
* Profit tracking
* Monthly sales trends
* Inventory valuation

This helps pharmacy owners understand sales performance and profitability.

---

# 🚀 Core Features

## 💊 Medicine Management

The system provides a complete medicine management module.

Capabilities include:

* Add new medicines
* Edit medicine details
* Delete medicines
* Automatic **Medicine Code Generation**
* Track manufacturers
* Maintain batch numbers
* Monitor expiry dates
* Track GST percentage
* Manage purchase and selling prices
* Profit margin tracking
* Maintain stock quantities

---

## 📦 Inventory Management

The inventory system automatically tracks stock levels.

Features include:

* Real-time stock updates
* Automatic stock deduction during billing
* Low stock alerts
* Expiry monitoring
* Prevent negative stock
* Inventory value calculation

---

## 🧾 Smart Billing System

The billing module simplifies pharmacy sales operations.

Capabilities include:

* Create pharmacy bills
* Add multiple medicines per bill
* Automatic GST calculation
* Patient information support
* Invoice generation
* Bill history tracking
* Printable invoices

---

## 📊 Sales Analytics

The analytics module helps pharmacy owners monitor business performance.

Capabilities include:

* Top selling medicines tracking
* Revenue analytics
* Profit calculation
* Monthly sales trend charts
* Inventory value insights

---

## 👥 Staff Management

Pharmacy owners can manage staff within the system.

Features include:

* Add staff members
* Assign roles
* Staff login authentication
* Permission-based system access

Supported roles:

* Owner
* Pharmacist
* Staff

---

## 🏥 Multi-Pharmacy Support

The system supports **multi-tenant pharmacy architecture**.

Each pharmacy operates independently with:

* Separate medicine inventory
* Independent billing records
* Dedicated staff accounts
* Custom pharmacy configuration

---

## ⚙️ Pharmacy Settings

The system allows configuration of pharmacy information including:

* Pharmacy name
* Address
* Contact information
* GST configuration
* Billing information

These details automatically appear on invoices.

---

# 🔄 Application Working Flow

The following diagram shows the **happy flow of the system**.

```
User Login
     ↓
Dashboard Overview
     ↓
Medicine Inventory Management
     ↓
Add / Update Medicines
     ↓
Inventory Ready for Sale
     ↓
Create New Bill
     ↓
Select Medicines + Quantity
     ↓
Automatic GST & Price Calculation
     ↓
Save Bill
     ↓
Invoice Generated
     ↓
Inventory Stock Updated
     ↓
Sales Data Stored
     ↓
Sales Analytics & Reports Generated
```

This flow represents the **core pharmacy business lifecycle**:

```
Inventory → Sales → Analytics
```

---

# 🧠 System Architecture

The project follows **MVC (Model – View – Controller)** architecture.

```
Client Browser
       ↓
HTML / Thymeleaf Templates (View)
       ↓
Spring Boot Controllers
       ↓
Service Layer
       ↓
Repository Layer
       ↓
MySQL Database
```

### Architecture Benefits

* Clean separation of concerns
* Maintainable codebase
* Modular structure
* Easy scalability

---

# 🛠️ Technology Stack

### Backend

* Java
* Spring Boot
* Spring MVC
* Spring Data JPA

### Frontend

* HTML
* CSS
* JavaScript
* Thymeleaf

### Database

* MySQL

### Build Tool

* Maven

### Server

* Embedded Apache Tomcat

---

# 🔐 Security Features

* Session-based authentication
* Role-based access control
* Secure login system
* Input validation
* Controlled staff access

---

# 💼 Commercial Availability

This software is available for **commercial licensing and deployment**.

If you are interested in purchasing or deploying this pharmacy system, please contact the author.

---

# 👨‍💻 Author

**Rezaul Karim Khan**

Software Engineer | Java | Spring Boot | Full Stack Development

🌐 Portfolio
https://rezaul.online

💻 GitHub
https://github.com/rezaul-code

🔗 LinkedIn
https://linkedin.com/in/rezaul-khan

---

# ⭐ Support

If you like the concept of this project, please **star the repository** ⭐
