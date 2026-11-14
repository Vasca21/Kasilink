# Kasilink

Kasilink is a web-based e-commerce platform that connects local sellers with customers through an online marketplace.

## Features

- Seller management
- Product listings
- Inventory management
- Role-based access control

## Technology Stack

- HTML, CSS, and JavaScript
- PHP
- MySQL
- Bootstrap

## Getting Started

Setup and installation instructions will be added here.

## Project Description

Kasilink aims to help local sellers manage their products and inventory while giving customers a place to discover and shop from local businesses.

==================================================
KASILINK - TOWNSHIP MARKETPLACE SYSTEM
==================================================

Project Name:
KasiLink

Description:
KasiLink is an e-commerce marketplace platform designed to connect township businesses, buyers, and sellers in one secure environment.

==================================================
FEATURES
==================================================

BUYER FEATURES
--------------
- Register Account
- Login
- Browse Products
- Add Products to Cart
- Make Payments
- View Orders
- View Approved Businesses

SELLER FEATURES
---------------
- Register Account
- Login
- Register Business
- Upload Products
- Manage Products
- View Business Status
- View Orders

ADMIN FEATURES
--------------
- Login
- Dashboard
- Manage Users
- Approve Businesses
- Reject Businesses
- Manage Products
- View Reports
- System Settings

==================================================
TECHNOLOGIES USED
==================================================

Frontend
---------
HTML5
CSS3
JavaScript

Backend
--------
PHP 8+

Database
---------
MySQL

Server
------
XAMPP

==================================================
DATABASE NAME
==================================================

kasilink

==================================================
MAIN WEBSITE FOLDER
==================================================

main/

Files:
config.php
index.php
register.php
login.php
logout.php

Products.php
cart.php
payment.php
orders.php

business.php
business_directory.php

seller_dashboard.php
upload_product.php

styles.css
script.js

==================================================
ADMIN WEBSITE FOLDER
==================================================

admin/

Files:
login.php
dashboard.php

users.php
business.php
products.php
sidebar.php
logout.php

styles.css
script.js

==================================================
DATABASE TABLES
==================================================

users
-----
userID
fullname
email
password
role
created_at

products
--------
productID
productName
description
price
sellerID
productImage
category
stock
status
created_at

businesses
----------
id
owner_id
business_name
category
description
phone
email
address
logo
status
created_at

cart
----
id
user_id
product_id
quantity
created_at

orders
------
orderID
userID
productID
status
businessID
paymentID
paymentmethod
total_amount
created_at

payment
-------
paymentID
orderID
amount
paymentMethod
paymentStatus

admins
------
id
fullname
email
password
created_at

==================================================
INSTALLATION
==================================================

1. Install XAMPP

2. Start:
   - Apache
   - MySQL

3. Open phpMyAdmin

4. Create Database:
   kasilink

5. Import SQL file

6. Copy project folder to:
   C:\xampp\htdocs\kasilink

7. Open browser:
   Main Website:
   http://localhost/kasilink/main

   Admin Website:
   http://localhost/kasilink/admin

==================================================
DEFAULT USER FLOW
==================================================

Buyer:
Register
-> Login
-> Browse Products
-> Add To Cart
-> Payment
-> Orders

Seller:
Register
-> Login
-> Register Business
-> Admin Approval
-> Upload Products
-> Manage Products

Admin:
Login
-> Dashboard
-> Approve Businesses
-> Manage Users
-> Reports

==================================================
AUTHOR
==================================================

Project:
KasiLink Township Marketplace

Version:
1.0

==================================================
END OF FILE
==================================================
