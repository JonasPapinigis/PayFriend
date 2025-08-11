# PayFriend
A simplified payment platform built with Django, inspired by PayPal but without real money transactions. This project demonstrates secure web application development with comprehensive security features, database management, and cloud deployment.


# PayFriend - Django Payment Platform

A simplified payment platform built with Django, inspired by PayPal but without real money transactions. This project demonstrates secure web application development with comprehensive security features, database management, and cloud deployment.

<img width="599" height="275" alt="image" src="https://github.com/user-attachments/assets/dc8271d5-8be3-4e64-b7ad-85edd5dae39d" />
<img width="609" height="221" alt="image" src="https://github.com/user-attachments/assets/de7dcef4-8b4e-473a-b25c-53a09d3204d0" />
<img width="606" height="448" alt="image" src="https://github.com/user-attachments/assets/e3d43a70-123f-4e8d-a71b-aa7b16ed0979" />



## 🚀 Features

### Core Functionality
- **User Registration & Authentication**: Secure user account creation with email validation
- **Multi-Currency Support**: GBP, USD, EUR with automatic conversion
- **Money Transfers**: Send money between users with real-time balance updates
- **Payment Requests**: Request money from other users with notification system
- **Transaction History**: Complete transaction tracking and audit trail
- **Admin Dashboard**: Comprehensive administrative interface

### Security Features
- **HTTPS Support**: SSL certificate integration for secure connections
- **CSRF Protection**: Built-in Cross-Site Request Forgery protection
- **XSS Prevention**: Django template auto-escaping
- **SQL Injection Prevention**: Django ORM and form validation
- **Clickjacking Protection**: X-Frame-Options headers
- **Password Security**: SHA256 hashing for password storage
- **Session Management**: Secure session handling and cleanup

### Technical Features
- **ACID Compliance**: Database transactions with atomicity guarantees
- **RESTful API**: Currency conversion API endpoints
- **Responsive UI**: Bootstrap-based responsive design with Crispy Forms
- **Database Support**: SQLite (development) and PostgreSQL (production)
- **Cloud Deployment**: AWS EC2 integration
- **Real-time Notifications**: User notification system for transactions

## 🛠️ Technology Stack

- **Backend**: Django 4.x, Python 3.x
- **Frontend**: HTML5, CSS3, Bootstrap, Crispy Forms
- **Database**: SQLite (development), PostgreSQL (production)
- **Security**: HTTPS/SSL, Django security middleware
- **Deployment**: AWS EC2, Nginx, Gunicorn
- **Version Control**: Git

## 📋 Prerequisites

- Python 3.8+
- Django 4.x
- PostgreSQL (for production)
- SSL certificate (for HTTPS)
- AWS account (for deployment)

# Installation

## Clone and Navigate to Project

```bash
git clone https://github.com/JonasPapinigis/PayFriend.git
cd webapps2025
```

## Install Dependencies
```bash
pip install -r requirements.txt
```

## Database Configuration
```bash
# Run migrations
python manage.py makemigrations
python manage.py migrate

python manage.py createsuperuser
```

## Launch Server
```bash
python manage.py runserver_plus --cert-file cert.pem --key-file key.pem

python manage.py runserver
```
