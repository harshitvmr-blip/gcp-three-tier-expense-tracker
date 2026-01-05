# GCP Three-Tier Expense Tracker

A cloud-based Expense Tracker web application deployed on **Google Cloud Platform (GCP)**
using a **three-tier architecture** (Frontend, Backend, Database).

This project was developed during my **Summer Internship** as part of my BCA program.

---

## 📌 Project Overview

The Expense Tracker helps users record, categorize, and analyze their daily expenses
using a secure, scalable, and cloud-native architecture.

The application is deployed on **GCP VM instances** behind a **Load Balancer** with
**Cloud SQL (MySQL)** as the backend database.

---

## 🏗 Three-Tier Architecture

### Frontend
- HTML, CSS, JavaScript
- Hosted on GCP VM

### Backend
- Python Flask Framework
- Gunicorn (WSGI Server)
- NGINX (Reverse Proxy)

### Database
- Cloud SQL (MySQL)
- Private IP connectivity

📷 Architecture Diagram  
![Architecture](docs/architecture.png)

---

## ⚙ Technologies Used

- Google Cloud Platform (GCP)
- Compute Engine (VM Instances)
- Cloud SQL (MySQL)
- Linux (Debian)
- Flask & SQLAlchemy
- NGINX & Gunicorn
- Git & GitHub

---

## ✨ Key Features

- Add, edit, and delete expenses
- Categorize expenses (Food, Transport, Utilities, etc.)
- Generate monthly and category-based reports
- Secure cloud database storage
- Accessible from anywhere via cloud deployment

---

## 🗄 Database Design

Entities:
- Users
- Expenses
- Categories

📷 ERD Diagram  
![ERD](docs/erd.png)

---

## 🚀 Deployment Summary

1. Created VPC, subnets, and firewall rules
2. Launched VM instances on GCP
3. Installed and configured NGINX and Gunicorn
4. Set up Cloud SQL with private IP
5. Connected Flask backend to Cloud SQL
6. Exposed application using Load Balancer

Detailed steps → `deployment/deployment-steps.md`

---

## 🧠 Learning Outcomes

- Real-world implementation of three-tier architecture
- Hands-on experience with GCP infrastructure
- Cloud networking (IP addressing, NAT, firewall rules)
- Linux server administration
- GitHub-based version control workflow

---

## 🔮 Future Enhancements

- Two-factor authentication (2FA)
- Budget alerts and notifications
- AI-based spending insights
- Mobile application support
