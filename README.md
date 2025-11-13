🛒 TrendKart – Full-Featured E-Commerce Web Application

TrendKart is a fully functional e-commerce web application built using Django, designed to provide a seamless shopping experience with features like product browsing, user authentication, cart management,checkout, and order tracking. The project also includes category management, variations (sizes/colors), email notifications, and secure user sessions.


🚀 Features

✔ User Registration & Login

✔ Product Listing with Categories

✔ Product Detail Pages

✔ Add to Cart / Remove from Cart

✔ Cart Counter & Session Handling

✔ Checkout & Order Summary

✔ Payment Integration (Razorpay/PayPal optional)

✔ User Profile & Order History

✔ Email Verification & Password Reset

✔ Admin Panel for Products, Categories, Orders

✔ Image Upload for Products & Categories

✔ Fully Responsive Frontend


🛠️ Technologies Used

Python (Django Framework)

HTML, CSS, Bootstrap

SQLite (default) or PostgreSQL (optional)

Pillow (for image handling)

Django Admin

Email Services (Gmail SMTP)

Boto3 / AWS S3 (optional – only if enabled in settings)



📂 Project Structure
TrendKart/
│── accounts/        # Authentication & User Management
│── category/        # Product Categories
│── store/           # Product Listing & Details
│── carts/           # Shopping Cart Logic
│── orders/          # Order Processing
│── templates/       # HTML Templates
│── static/          # CSS, JS, Images
│── media/           # Uploaded Images
│── greatkart/       # Main Project Settings & URLs
└── manage.py
