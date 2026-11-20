# bike-rental
# 🏍️ Premium Moto Rental

**A modern motorcycle rental and management platform built with Python, Django, and MySQL.**

Premium Moto Rental is a web application designed to simplify motorcycle rentals in Morocco. It connects customers with premium motorcycles and provides a centralized system for managing motorcycles, reservations, customers, and payments.

The platform aims to deliver a smooth booking experience for customers while giving administrators the tools they need to manage daily rental operations.

> 🚧 **Project Status:** In Development

---

## 📌 Project Overview

The goal of this project is to develop a complete motorcycle rental platform where customers can explore available motorcycles, check rental details, and submit reservations online.

On the administrative side, the platform will provide a management dashboard to control the motorcycle fleet, monitor bookings, manage customers, and track business activities.

The initial fleet is planned to include motorcycles from brands such as:

- BMW
- Yamaha
- Honda
- Kawasaki

The platform is designed with future expansion in mind, allowing the business to add more motorcycles, services, and features as it grows.

---

## ✨ Main Features

### 👤 Customer Features

- User registration and authentication.
- Browse available motorcycles.
- View detailed motorcycle information.
- Search and filter motorcycles.
- Check motorcycle availability.
- Select rental dates.
- Calculate rental prices automatically.
- Submit rental reservations.
- View booking history.
- Manage personal information.

### ⚙️ Administration Features

- Admin dashboard.
- Add, edit, and remove motorcycles.
- Manage motorcycle categories.
- View and manage customer accounts.
- Approve or reject reservations.
- Track rental statuses.
- Manage payments.
- Monitor motorcycle maintenance.
- View business statistics and reports.

### 🔐 Security

- Secure authentication.
- Role-based access control.
- Form validation.
- CSRF protection.
- Secure password management.
- Protection against common web vulnerabilities.

---

## 🛠️ Technologies

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Django | Backend web framework |
| MySQL | Relational database |
| HTML5 | Website structure |
| CSS3 | Styling |
| JavaScript | Interactive functionality |
| Tailwind CSS | Responsive user interface |
| Git & GitHub | Version control |

---

## 🏗️ Project Architecture

The application follows a modular Django architecture.

```text
premium-moto-rental/
│
├── config/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── accounts/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── forms.py
│
├── motorcycles/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── forms.py
│
├── bookings/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── forms.py
│
├── payments/
│
├── dashboard/
│
├── templates/
├── static/
├── media/
│
├── manage.py
├── requirements.txt
├── .env.example
└── README.md
```

*The structure may evolve as development progresses.*

---

## 🚀 Getting Started

Follow these instructions to run the project locally.

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/premium-moto-rental.git

cd premium-moto-rental
```

### 2. Create a virtual environment

```bash
python3 -m venv venv
```

Activate it:

**macOS / Linux**

```bash
source venv/bin/activate
```

**Windows**

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure MySQL

Create a MySQL database:

```sql
CREATE DATABASE premium_moto_rental;
```

Configure your database credentials in your environment variables.

Example `.env` configuration:

```env
SECRET_KEY=your-secret-key
DEBUG=True

DB_NAME=premium_moto_rental
DB_USER=your-mysql-username
DB_PASSWORD=your-mysql-password
DB_HOST=localhost
DB_PORT=3306
```

Make sure your Django settings are configured to read these environment variables.

### 5. Apply database migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 6. Create an administrator account

```bash
python manage.py createsuperuser
```

### 7. Start the development server

```bash
python manage.py runserver
```

Open your browser:

```text
http://127.0.0.1:8000/
```

The Django administration panel will be available at:

```text
http://127.0.0.1:8000/admin/
```

---

## 📅 Development Roadmap

- [ ] Initialize Django project.
- [ ] Configure MySQL database.
- [ ] Design database models and relationships.
- [ ] Implement customer authentication.
- [ ] Develop the homepage.
- [ ] Build the motorcycle catalogue.
- [ ] Implement motorcycle details pages.
- [ ] Develop the booking system.
- [ ] Implement availability verification.
- [ ] Build the customer dashboard.
- [ ] Develop the administration dashboard.
- [ ] Implement payment management.
- [ ] Add motorcycle maintenance management.
- [ ] Perform security and functionality testing.
- [ ] Deploy the application.

---

## 🔮 Future Improvements

Potential future features include:

- Online payment integration.
- Email notifications and booking confirmations.
- WhatsApp integration.
- Customer reviews and ratings.
- Promotional codes and discounts.
- Advanced analytics and business reports.
- Multilingual support (French, English, and Arabic).
- Mobile-friendly booking experience.

---

## 🎯 Project Objectives

This project aims to:

1. Digitalize motorcycle rental operations.
2. Make motorcycle reservations easier and faster.
3. Improve fleet and customer management.
4. Provide a secure and reliable booking platform.
5. Build a scalable solution that can support business growth.

---

## 🤝 Contributing

Contributions, suggestions, and ideas are welcome.

If you would like to contribute:

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Submit a Pull Request.

---

## 👨‍💻 Author

**Your Name**

GitHub: @yassine-abdeljalill(https://github.com/yassine-abdeljalill)

---

## 📄 License

This project is currently under development. Licensing details will be added later.

---

<p align="center">
  <strong>Premium Moto Rental</strong><br>
  Ride More. Explore Further.
</p>
