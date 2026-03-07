# 💊 Pharmacy Management System

![Dashboard](screenshots/dashboard.png)

![Billing](screenshots/new-bill.png)

![Inventory](screenshots/inventory.png)

---

## ⚠️ Important Notice

This repository is a **public showcase repository** created to demonstrate the **features, architecture, and working flow** of the Pharmacy Management System.

The **actual implementation repository containing the complete source code is private** to protect the original implementation and intellectual property.

If you are interested in using or purchasing the system, you can contact the author.

This repository contains:

* Feature overview
* System architecture
* Application screenshots
* Working flow explanation
* Technical stack details

---

# 📌 Project Overview

The **Pharmacy Management System** is a modern **digital solution for pharmacy operations** designed to replace traditional manual registers and spreadsheets.

The system enables pharmacies to efficiently manage:

* Medicine inventory
* Billing and invoice generation
* Stock monitoring
* Staff management
* Pharmacy configuration

The application is built using **Java, Spring Boot, HTML, CSS, JavaScript, and MySQL**, following a **clean MVC architecture** to ensure scalability, performance, and maintainability.

It is designed to be **simple for pharmacy staff to use while maintaining powerful backend capabilities**.

---

# 🚀 Core Features

## 💊 Medicine Management

The system provides a complete module for managing pharmacy medicines.

Capabilities include:

* Add new medicines
* Edit existing medicine details
* Delete medicines
* Manage medicine categories
* Store manufacturer details
* Track batch numbers
* Maintain expiry dates
* Maintain GST percentage
* Track medicine pricing
* Manage medicine stock quantity

Each medicine record includes:

* Medicine name
* Medicine type
* Manufacturer
* Batch number
* Expiry date
* Price per unit
* GST percentage
* Stock quantity

---

## 📦 Inventory Management

The inventory system automatically tracks medicine stock levels and ensures accurate availability.

Key capabilities:

* Real-time stock updates
* Automatic stock deduction during billing
* Low stock monitoring
* Expiry date tracking
* Inventory visibility
* Prevent negative stock during billing

This ensures pharmacy staff always know the **exact availability of medicines**.

---

## 🧾 Smart Billing System

The billing module enables pharmacies to quickly generate medicine invoices for customers.

Features include:

* Create new pharmacy bills
* Add multiple medicines in a single bill
* Automatic GST calculation
* Quantity-based pricing
* Patient information support
* Bill history storage
* Invoice generation
* Print-friendly invoice format

The system automatically calculates:

* Item subtotal
* GST amount
* Total bill value

This reduces manual calculations and speeds up the checkout process.

---

## 👥 Staff Management

The system includes a **staff management module** to help pharmacy owners control access to the system.

Capabilities include:

* Add staff members
* Assign staff roles
* Invite staff to join the pharmacy
* Staff login authentication
* Manage staff permissions

Supported roles include:

* Owner
* Pharmacist
* Staff

This ensures secure and organized operations.

---

## 🏥 Multi-Pharmacy Support

The application supports **multi-pharmacy architecture**, allowing multiple pharmacies to operate independently within the same platform.

Features include:

* Pharmacy registration
* Separate pharmacy environments
* Independent medicine inventories
* Separate billing records
* Dedicated pharmacy configuration

Each pharmacy manages its **own medicines, staff, and billing data**.

---

## ⚙️ Pharmacy Settings

The system includes a configuration module where pharmacies can manage:

* Pharmacy name
* Address
* Contact information
* Billing information
* GST configuration

These settings automatically appear on generated invoices.

---

## 📊 Dashboard

The dashboard provides a quick overview of pharmacy operations.

Information displayed includes:

* Total medicines available
* Low stock alerts
* Total generated bills
* Recent billing activities
* Inventory overview

This allows pharmacy staff to **monitor the system instantly after login**.

---

## 🔍 Smart Medicine Search

The system includes a fast search feature to improve billing speed.

Capabilities include:

* Instant medicine search
* Autocomplete suggestions
* Quick inventory lookup
* Fast medicine selection during billing

This significantly **reduces billing time and improves efficiency**.

---

# 🔄 Application Working Flow

The system workflow is designed to match real pharmacy operations.

### 1️⃣ User Login

Pharmacy staff log into the system using secure authentication.

After login, the user session is created and the user is redirected to the dashboard.

---

### 2️⃣ Dashboard Overview

The dashboard displays important information including:

* Inventory overview
* Medicine count
* Billing statistics
* Alerts and notifications

---

### 3️⃣ Medicine Inventory Management

Staff manage medicines by:

* Adding new medicines
* Updating stock levels
* Editing medicine details
* Tracking expiry dates

All changes are stored in the database and reflected across the system.

---

### 4️⃣ Billing Process

When a customer purchases medicines:

1. Staff opens the **New Billing interface**

2. Medicines are searched using **autocomplete search**

3. Staff selects medicines and enters quantity

4. The system automatically calculates:

   * Item price
   * GST amount
   * Bill total

5. The bill is saved in the database.

---

### 5️⃣ Invoice Generation

Once the bill is completed, the system generates a **clean printable invoice** containing:

* Pharmacy information
* Patient details
* Medicine list
* GST breakdown
* Grand total

Invoices can be printed or stored for record keeping.

---

### 6️⃣ Automatic Inventory Update

After a bill is generated:

* Medicine stock is automatically reduced
* Inventory data is updated
* Low stock alerts are triggered if needed

This ensures the inventory always remains accurate.

---

# 🧠 System Architecture

The project follows the **MVC (Model – View – Controller)** architecture.

```
Client Browser
       ↓
Thymeleaf Templates (View)
       ↓
Spring Boot Controllers
       ↓
Service Layer
       ↓
Repository Layer (JPA)
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

## Backend

* Java
* Spring Boot
* Spring MVC
* Spring Data JPA

## Frontend

* HTML
* CSS
* JavaScript
* Thymeleaf

## Database

* MySQL

## Build Tool

* Maven

## Server

* Embedded Apache Tomcat

---

# 🔐 Security Features

* Session-based authentication
* Role-based access control
* Secure login system
* Input validation
* Controlled staff access

---

# 🔮 Future Improvements

Planned enhancements include:

* Barcode scanner integration
* Advanced sales reports
* Expiry alerts
* Low stock notifications
* PDF invoice export
* REST API integration
* Android mobile application
* Cloud deployment

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

# 💼 Commercial Availability

This software is available for **commercial licensing**.

If you are interested in purchasing the system or integrating it into your pharmacy business, please contact the author.

---

# ⭐ Support

If you like the project concept, please **star this repository** ⭐
