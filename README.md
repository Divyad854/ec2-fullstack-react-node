# Full-Stack Web Application on AWS EC2

## 🚀 Project Overview
This project is a full-stack web application built using React and Node.js,
deployed on AWS EC2 instances.

## 🏗 Architecture
- Frontend: React (EC2)
- Backend: Node.js + Express (EC2)
- Two-tier architecture
- Secure communication using Security Groups
- IAM Roles (no access keys)

## 🛠 Tech Stack
- React
- Node.js
- Express
- AWS EC2
- IAM
- GitHub

## ✨ Features
- Frontend–Backend communication
- REST API
- Error handling
- Styled UI
- Secure AWS setup

## 📌 Learning Outcomes
- AWS EC2 deployment
- Networking & security groups
- IAM roles & permissions
- Real-world debugging


## 🔧 Implementation Steps

### 1️⃣ EC2 Instance Setup
- Launched **two EC2 instances** (Frontend & Backend)
- Used Amazon Linux AMI
- Assigned public IPs
- Configured separate Security Groups

---

### 2️⃣ Security Group Configuration
- Frontend EC2:
  - Allow HTTP (80) / React port (3000)
  - Allow SSH (22) from own IP
- Backend EC2:
  - Allow SSH (22) from own IP
  - Allow API port (5000) from Frontend EC2 / public IP

---

### 3️⃣ IAM Role Configuration
- Created IAM roles for EC2
- Attached roles to instances
- No access keys used in application code

---

### 4️⃣ Backend Deployment (Node.js)
- Installed Node.js and dependencies
- Built REST API using Express
- Configured backend to listen on port 5000
- Verified API accessibility via browser and curl

---

### 5️⃣ Frontend Deployment (React)
- Installed Node.js
- Created React application
- Connected frontend to backend using public API endpoint
- Deployed frontend using development server / production build

---
