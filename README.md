# 🛍️ Artisync — Django Artisan Shop Platform
![Build](https://img.shields.io/badge/build-passing-brightgreen.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Made with Django](https://img.shields.io/badge/Made%20with-Django-092E20?logo=django)
![Database](https://img.shields.io/badge/Database-MySQL-blue.svg)

A modern **e-commerce platform for artisans** built with **Django**, **MySQL**, **HTML**, **CSS**, and **Bootstrap**.  
Artisync helps local artisans showcase, manage, and sell their handmade products through a simple yet powerful online shop interface.

---

## ✨ Features

### 👨‍💼 Admin
- Manage artisans, products, and customer accounts.  
- View, approve, or delete product listings.  
- Track orders and manage transactions.  
- View insights and sales statistics from the dashboard.

### 🧑‍🎨 Artisans
- Create and manage artisan profiles.  
- Add, update, or remove handmade product listings.  
- View order requests and manage product availability.  
- Track product performance through simple metrics.

### 🛒 Customers
- Browse and search for artisan products.  
- Add items to cart, place orders, and view order history.  
- Manage personal profiles and delivery addresses.  
- Secure checkout process and responsive design.

---

## ⚙️ Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/heyitsmanal/django-artisanShop-artisync.git
cd django-artisanShop-artisync
```
### 2️⃣ Create and Activate a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate
``` 
### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 4️⃣ Apply Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```
### 5️⃣ Create Superuser
```bash
python manage.py createsuperuser
```
### 6️⃣ Run the Server
```bash
python manage.py runserver
```
