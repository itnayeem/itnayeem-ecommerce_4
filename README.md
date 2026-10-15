# 🛒 IT Nayeem E-Commerce Platform

[![Laravel](https://img.shields.io/badge/Framework-Laravel-red?style=for-the-badge&logo=laravel)](https://laravel.com)
[![PHP](https://img.shields.io/badge/PHP-8.x-777bb4?style=for-the-badge&logo=php)](https://php.net)
[![MySQL/MariaDB](https://img.shields.io/badge/Database-MySQL%20%2F%20MariaDB-4479A1?style=for-the-badge&logo=mysql)](https://mariadb.org)
[![License](https://img.shields.io/badge/License-Proprietary-blue?style=for-the-badge)](https://itnayeem.com.bd/)
[![Website](https://img.shields.io/badge/Website-itnayeem.com.bd-green?style=for-the-badge)](https://itnayeem.com.bd/)

A robust, enterprise-grade, multi-purpose E-Commerce platform developed and maintained by **[IT Nayeem](https://itnayeem.com.bd/)**. Designed with scalability, rich aesthetics, ultra-fast performance, and a seamless shopping experience for modern online businesses.

---

## 🏢 About IT Nayeem

**IT Nayeem** is a premier software development, digital solutions, and IT consultancy provider based in Bangladesh. We specialize in building cutting-edge web applications, bespoke e-commerce platforms, custom ERPs, and cloud architecture tailored for businesses looking to scale.

* 🌐 **Official Website:** [www.itnayeem.com.bd](https://itnayeem.com.bd/)
* 📞 **Helpline & Contact:** `+8801511777744`
* ✉️ **Support Email:** [support@itnayeem.com.bd](mailto:support@itnayeem.com.bd)

---

## 🚀 Key Features

* **Advanced Product Catalog:** Multi-category, brands, digital and physical products, flash sales, variants, attributes, and inventory tracking.
* **Order & Checkout Workflow:** Guest & customer checkout, automated shipping calculation, multi-currency support, order tracking, and invoice PDF generation.
* **Payment Gateways:** Integrated with bKash, Nagad, Rocket, manual bank transfers, COD, and international gateways.
* **Multi-language & RTL Support:** Fully localized (including English and Bangla), with dynamic RTL support.
* **Responsive & Mobile-Ready:** Fully responsive layout across desktops, tablets, and smartphones.
* **Dynamic Media Manager:** Integrated file upload manager with automatic placeholder fallbacks for missing assets.
* **Administrative Control:** Full-featured analytics dashboard, role-based access control, marketing coupons, and customer management.

---

## 🛠️ Technology Stack & Architecture

| Layer | Technologies |
| :--- | :--- |
| **Backend Framework** | Laravel 8.x / 9.x (PHP 8.x compatible) |
| **Frontend Engine** | Blade Templating, Vanilla CSS, Bootstrap 4/5, jQuery |
| **Database** | MariaDB 10.11+ / MySQL 8.0+ |
| **Asset Pipeline** | Laravel Mix / Webpack |
| **Server Support** | Nginx, Apache, PHP Built-in Server with custom router |

---

## 🔐 Admin Panel Access & Credentials

The administrative control center allows administrators to manage products, categories, orders, customers, business settings, and marketing banners.

* **Admin Panel URL:** `/admin` (Redirects to `/login`)
* **Admin Email:** `support@itnayeem.com.bd`
* **Admin Password:** `12345678`

> ⚠️ **Important:** After first setup in production, remember to change the admin password from the Admin Profile settings.

---

## ⚙️ Installation & Setup Guide

### 1. Prerequisites
* **PHP:** `>= 8.0` (with extensions: `pdo_mysql`, `mbstring`, `openssl`, `tokenizer`, `xml`, `ctype`, `json`, `curl`, `gd`)
* **Composer:** `>= 2.0`
* **Database:** MySQL `>= 5.7` or MariaDB `>= 10.5`
* **Web Server:** Apache, Nginx, or PHP CLI Server

### 2. Clone Repository
```bash
git clone git@github.com:itnayeem/itnayeem-ecommerce_4.git
cd itnayeem-ecommerce_4
```

### 3. Environment Configuration
Copy `.env.example` to `.env`:
```bash
cp .env.example .env
```

Open `.env` and set your database connection:
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=it_nayeem_db
DB_USERNAME=your_database_username
DB_PASSWORD=your_database_password
```

### 4. Database Import
Create the database and import the included SQL dump file:
```bash
mysql -u your_username -p it_nayeem_db < it_nayeem_db.sql
```

### 5. Clear and Cache Application
```bash
php artisan config:clear
php artisan cache:clear
php artisan view:clear
```

### 6. Run the Application Locally
You can use the built-in server router:
```bash
php -S 0.0.0.0:8005 server.php
```
Or with Laravel Artisan:
```bash
php artisan serve --port=8005
```

Visit the website at: **`http://127.0.0.1:8005`**

---

## 📞 Support & Inquiries

For technical support, custom software development, or business inquiries, reach out through our official channels:

* 🌐 **Website:** [https://itnayeem.com.bd/](https://itnayeem.com.bd/)
* 📞 **Phone:** `+8801511777744`
* ✉️ **Email:** [support@itnayeem.com.bd](mailto:support@itnayeem.com.bd)

---

<div align="center">
  <p>© 2026 <strong>IT NAYEEM</strong>. All rights reserved. | Developed by <a href="https://itnayeem.com.bd/">IT Nayeem</a></p>
</div>
