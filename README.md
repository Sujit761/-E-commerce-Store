# 🛍️ E-commerce Store

A full-featured, modern E-commerce platform built with **Django**, designed to provide a seamless shopping experience. From browsing products to secure checkout and order tracking, this application covers the entire customer journey.

---

## 🌟 Key Features

### 🔐 User Authentication
- **Secure Registration & Login**: Users can create accounts and securely log in.
- **Profile Management**: Maintain user-specific data and order history.

### 📦 Product Management
- **Dynamic Catalog**: Browse a wide range of products organized by categories.
- **Detailed Product Pages**: View high-quality images, descriptions, and pricing.
- **Search & Filter**: Easily find products using categories and search functionality.

### 🛒 Shopping Experience
- **Interactive Cart**: Add, remove, and update item quantities in real-time.
- **Persistent Cart**: Cart contents are saved for logged-in users.

### 💳 Checkout & Orders
- **Streamlined Checkout**: A smooth, multi-step process for placing orders.
- **Order Tracking**: Users can view their order history and status in their dashboard.
- **Automated Calculations**: Taxes and shipping costs calculated during checkout.

---

## 🛠️ Technology Stack

- **Backend**: [Django 4.x](https://www.djangoproject.com/) (Python)
- **Database**: SQLite (Default) / PostgreSQL (Optional)
- **Frontend**: HTML5, CSS3 (Vanilla CSS), JavaScript
- **Icons/UI**: Modern responsive design

---

## 🚀 Getting Started

Follow these steps to get the project running locally:

### 1. Clone the Repository
```bash
git clone https://github.com/Sujit761/-E-commerce-Store.git
cd -E-commerce-Store
```

### 2. Set Up Virtual Environment
```bash
# Create venv
python -m venv venv

# Activate venv (Windows)
venv\Scripts\activate

# Activate venv (Mac/Linux)
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Database Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Create Superuser (Admin Access)
```bash
python manage.py createsuperuser
```

### 6. Run Development Server
```bash
python manage.py runserver
```
Visit `http://127.0.0.1:8000` to see the store in action!

---

## 📂 Project Structure

```text
├── accounts/       # User profile and auth logic
├── cart/           # Shopping cart functionality
├── core/           # Core configurations and utilities
├── ecommerce/      # Main project settings
├── orders/         # Order processing and history
├── shop/           # Product catalog and display
├── static/         # CSS, JS, and Images
├── templates/      # HTML Templates
└── manage.py       # Django management script
```

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to:
1. Fork the project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the Branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

---

## 📧 Contact

**Sujit** - [GitHub Profile](https://github.com/Sujit761)

Project Link: [https://github.com/Sujit761/-E-commerce-Store](https://github.com/Sujit761/-E-commerce-Store)

---
*Built with ❤️ using Django*
