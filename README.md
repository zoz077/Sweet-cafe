# 🍰 Sweet Cafe

A full-stack e-commerce web application for a café, built with **Django 6.0**. Features user authentication, a shopping cart, dark/light theme toggle, and a clean responsive design.

\---

## ✨ Features

* 🛍️ **Product Catalog** — Browse all available sweets and pastries
* 🛒 **Shopping Cart** — Add, update, and remove items with live subtotal calculation
* 👤 **User Authentication** — Register, login with "Remember Me" option, and logout
* 🌓 **Theme Toggle** — Switch between light and dark mode, saved to localStorage
* 🔐 **Secure** — CSRF protection, password hashing, and session management
* 🖼️ **Media Uploads** — Product images managed via Django's media system
* ⚙️ **Admin Panel** — Full CRUD for products and orders via Django Admin

\---

## 🛠️ Tech Stack

|Layer|Technology|
|-|-|
|Backend|Django 6.0 (Python 3.14)|
|Frontend|HTML5, CSS3, Vanilla JS|
|Database|SQLite3|
|Media|Pillow|
|Fonts|Google Fonts (Merienda, Atma)|

\---

## 📁 Project Structure

```
SweetCafeNew/
├── sweetcafe/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
├── store/
│   ├── migrations/
│   ├── templates/store/
│   │   ├── base.html
│   │   ├── home.html
│   │   ├── login.html
│   │   ├── register.html
│   │   └── cart.html
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── admin.py
├── media/
├── manage.py
└── requirements.txt
```

\---

## 🚀 Getting Started

### 1\. Clone the repository

```bash
git clone https://github.com/zoz077/sweet-cafe.git
cd sweet-cafe
```

### 2\. Install dependencies

```bash
pip install -r requirements.txt
```

### 3\. Run migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 4\. Create a superuser

```bash
python manage.py createsuperuser
```

### 5\. Start the development server

```bash
python manage.py runserver
```

Open your browser at: `http://127.0.0.1:8000`

\---

## 🔧 Admin Panel

Go to `http://127.0.0.1:8000/admin` and log in with your superuser credentials to add and manage products.

\---

## 📍 URL Routes

|Route|Description|
|-|-|
|`/`|Home — product catalog|
|`/login/`|User login|
|`/register/`|New account registration|
|`/logout/`|Logout|
|`/cart/`|Shopping cart|
|`/admin/`|Admin dashboard|

\---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

\---

**Made with Zahraa Saheb using Django 6.0**

