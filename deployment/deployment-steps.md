# GCP Deployment Steps – Three Tier Architecture

## 1. Network Setup
- Create a VPC network
- Configure subnets
- Add firewall rules for HTTP/HTTPS traffic

## 2. VM Setup
- Launch Debian Linux VM instances
- Assign internal IPs
- Enable required ports

## 3. Backend Configuration
- Install Python, Flask, SQLAlchemy
- Configure Gunicorn as WSGI server
- Configure NGINX as reverse proxy

## 4. Database Setup
- Create Cloud SQL (MySQL) instance
- Enable private IP connectivity
- Create required database and tables

## 5. Application Deployment
- Deploy Flask application on VM
- Connect backend to Cloud SQL
- Test application locally

## 6. Load Balancer
- Configure GCP Load Balancer
- Attach backend VM
- Access application via public IP

