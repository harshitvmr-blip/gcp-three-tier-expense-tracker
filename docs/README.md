# GCP Three-Tier Expense Tracker

A cloud-based Expense Tracker web application deployed on **Google Cloud Platform (GCP)**
using a **three-tier architecture** with frontend, backend, and database layers.

---

## 📌 Project Overview
This project was developed during my **Summer Internship** and focuses on building
a scalable, secure, and cloud-native expense tracking system.

Users can:
- Record daily expenses
- Categorize spending
- Generate visual reports
- Access data securely from anywhere

The application is deployed on **GCP VM instances behind a Load Balancer**
with **Cloud SQL (MySQL)** as the database.

---

## 🏗 Three-Tier Architecture
**Frontend**
- HTML, CSS, JavaScript
- Hosted on GCP VM

**Backend**
- Flask (Python)
- Gunicorn (WSGI)
- NGINX reverse proxy

**Database**
- Cloud SQL (MySQL)
- Private IP connectivity

📷 Architecture Diagram:  
![Architecture](docs/architecture.png)

---

## ⚙ Technologies Used
- Google Cloud Platform (GCP)
- Compute Engine (VMs)
- Cloud SQL (MySQL)
- Linux (Debian)
- Flask & SQLAlchemy
- NGINX & Gunicorn
- Git & GitHub

---

## 🧠 Key Features
- Expense entry & categorization
- Monthly & category-based reports
- Secure cloud database
- Scalable cloud deployment
- Accessible via Load Balancer IP

---

## 🗄 Database Design
- Users
- Expenses
- Categories

📷 ERD Diagram:  
![ERD](docs/erd.png)

---

## 🚀 Deployment Summary
1. Created VPC, subnets, and firewall rules
2. Launched VM instances on GCP
3. Configured NGINX + Gunicorn
4. Set up Cloud SQL with private IP
5. Deployed application behind Load Balancer

Detailed steps → `deployment/deployment-steps.md`

---

## 📚 Learning Outcomes
- Hands-on experience with GCP infrastructure
- Real implementation of three-tier architecture
- Cloud networking (IP, NAT, firewall rules)
- Linux server administration
- GitHub version control in real projects

---

## 🔮 Future Improvements
- Two-factor authentication
- Budget alerts
- AI-based expense insights
- Mobile application integration
