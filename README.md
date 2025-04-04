# 🛒 eMazon - Online Shopping Platform (PHP + MySQL)

**eMazon** is a simple yet powerful e-commerce web application built using **PHP** and **MySQL**. It allows users to browse products, manage shopping carts, register/login, and place orders. Admin users can manage inventory via a lightweight dashboard.

---

## 🚀 Features

- 🧾 **User Authentication**: Registration and login with session-based auth.
- 🛍️ **Product Browsing**: Display products with categories and images.
- 🛒 **Shopping Cart**: Add, update, and remove items from the cart.
- ✅ **Checkout Page**: Order summary with basic confirmation.
- 👨‍💼 **Admin Dashboard**: Add, edit, or delete products.
- 🌐 **Responsive UI**: Built with HTML, CSS, and Bootstrap.

---

## 🛠️ Tech Stack

| Layer        | Technology       |
|--------------|------------------|
| Language     | PHP              |
| Database     | MySQL            |
| Frontend     | HTML, CSS, Bootstrap |
| Icons        | Font Awesome     |
| Auth         | PHP Sessions     |

---

## 📁 Project Structure

```bash
eMazon/
├── admin/             # Admin dashboard pages
│   ├── add_product.php
│   ├── edit_product.php
│   └── delete_product.php
├── auth/              # Login and registration pages
│   ├── login.php
│   └── register.php
├── cart/              # Cart management
│   ├── add.php
│   ├── remove.php
│   └── checkout.php
├── config/            # DB connection and config files
│   └── db.php
├── includes/          # Navbar, footer, common UI elements
│   ├── header.php
│   └── footer.php
├── pages/             # Product display and user-facing pages
│   └── home.php
├── emazon.sql         # SQL file to create DB and tables
└── index.php          # Entry point of the app



## 🛠️ Tech Stack

| Layer        | Technology       |
|--------------|------------------|
| Language     | PHP              |
| Database     | MySQL            |
| Frontend     | HTML, CSS, Bootstrap |
| Icons        | Font Awesome     |
| Auth         | PHP Sessions     |

---

## 📦 Installation & Configuration

### 🧰 Prerequisites

- PHP >= 7.x
- MySQL Server
- Apache (or any local server like XAMPP, WAMP, MAMP)
- phpMyAdmin (for importing the DB)
- Git (optional)

---

### 🔧 Setup Instructions

#### 1. Clone or Download the Repository

```bash
git clone https://github.com/Yonas21/eMazon-online-shopping.git
