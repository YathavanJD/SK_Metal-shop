# 🔩 SK Metal Shop — Full Stack Web Application

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)

> A complete full-stack web application for product, inventory, and order management for a metal hardware shop.

---

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Database Design](#database-design)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Author](#author)

---

## 📖 About the Project

SK Metal Shop is a full-stack web application developed to manage the day-to-day operations of a metal hardware shop. The system handles product listings, inventory tracking, customer orders, and provides an admin dashboard for managing the entire shop digitally.

This project demonstrates practical skills in full-stack web development using PHP and MySQL with a dynamic, user-friendly interface.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🛍️ Product Management | Add, edit, delete, and view metal products |
| 📦 Inventory Monitoring | Live stock tracking with low-stock alerts |
| 🛒 Shopping Cart | Add products to cart and manage quantities |
| 💳 Checkout System | Order placement and summary generation |
| 🔐 Customer Authentication | Secure user registration and login system |
| 🖥️ Admin Dashboard | Full control over products, orders, and users |
| 📊 Order Management | View and manage customer orders in real time |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, JavaScript |
| Backend | PHP |
| Database | MySQL |
| Server | Apache (XAMPP / WAMP) |

---

## 🗄️ Database Design

Key tables include:
- `users` — Customer and admin accounts
- `products` — Product catalog with stock levels
- `orders` — Customer order records
- `order_items` — Individual items within each order
- `cart` — Temporary cart storage per session

---

## ⚙️ Installation

### Prerequisites
- XAMPP or WAMP server installed
- PHP 7.4+
- MySQL 5.7+

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/YathavanJD/SK-Metal-Shop.git

# 2. Move the project to your server root
# For XAMPP: C:/xampp/htdocs/SK-Metal-Shop
# For WAMP:  C:/wamp64/www/SK-Metal-Shop

# 3. Import the database
# Open phpMyAdmin → Create database 'sk_metal_shop'
# Import the file: database/sk_metal_shop.sql

# 4. Configure database connection
# Edit config/db.php and update:
$host = "localhost";
$user = "root";
$password = "";
$database = "sk_metal_shop";

# 5. Start Apache and MySQL in XAMPP/WAMP
# Visit: http://localhost/SK-Metal-Shop
```

---

## 🚀 Usage

### Customer
1. Register or log in as a customer
2. Browse products by category
3. Add items to cart
4. Proceed to checkout and place order

### Admin
1. Log in with admin credentials
2. Manage products — add, edit, remove stock
3. View and update customer orders
4. Monitor inventory levels

---

## 📁 Project Structure

```
SK-Metal-Shop/
│
├── index.php               # Homepage / product listing
├── login.php               # Customer login
├── register.php            # Customer registration
├── cart.php                # Shopping cart
├── checkout.php            # Order placement
│
├── admin/
│   ├── dashboard.php       # Admin control panel
│   ├── products.php        # Product management
│   ├── orders.php          # Order management
│   └── users.php           # User management
│
├── config/
│   └── db.php              # Database connection
│
├── database/
│   └── sk_metal_shop.sql   # SQL dump file
│
├── assets/
│   ├── css/                # Stylesheets
│   ├── js/                 # JavaScript files
│   └── images/             # Product images
│
└── README.md
```

---

## 👨‍💻 Author

**Loganathan Yathavan**
- 📧 loganathanyathavan@gmail.com
- 🌐 [Portfolio](https://yathavanjd.github.io/Yathavan_Portfolio/)
- 💼 [LinkedIn](https://www.linkedin.com/in/yathavanloganathan03)
- 🐙 [GitHub](https://github.com/YathavanJD)

---

> ⭐ If you found this project useful, please consider giving it a star!
