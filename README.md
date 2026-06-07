# 🚂 IRCTC Clone - Indian Railways Booking System

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![JSP](https://img.shields.io/badge/JSP-007396?style=for-the-badge&logo=java&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

> ⚠️ **Disclaimer:** This project is built **only for educational & learning purposes**.
> This is NOT the official IRCTC website. No real tickets are booked or payments processed.
> IRCTC name & logo are trademarks of Indian Railways.

---

## 📌 About The Project

A full-stack **IRCTC Clone** web application built as an academic project.
It replicates core features of the Indian Railways ticketing system including
train search, seat selection, booking, payment simulation, and admin management.

---

## ✨ Features

### 👤 User Side
- 🔐 User Registration & Login with OTP Email Verification
- 🚆 Train Search between stations with date selection
- 💺 Interactive Seat Selection with live seat map
- 🎫 Ticket Booking with passenger details
- 💳 Payment via Stripe (Test Mode) & Dummy Pay
- 📄 PDF Ticket Download
- 📦 Booking History & Ticket Cancellation
- 🔍 PNR Status Check (Local + Live IRCTC API)
- 📡 Live Train Status Tracker
- 🍱 e-Catering / Food Ordering on train
- 🤖 AI Chatbot (Disha) powered by Google Gemini
- 👤 User Profile Management
- 📱 Fully Responsive - Mobile Friendly

### 🔧 Admin Side
- 🔐 Secure Admin Login Portal
- 📊 Dashboard with Revenue, Users, Trains stats
- 🚂 Manage Trains (Add, Edit, Delete)
- 👥 Manage Users (Block, Unblock, Delete)
- 📋 View All Bookings with Force Cancel option

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | JSP, HTML5, CSS3, Bootstrap 5, JavaScript |
| Backend | Java, Servlets, Jakarta EE |
| Database | MySQL with HikariCP Connection Pool |
| Server | Apache Tomcat 10.1 |
| Build Tool | Maven |
| Payment | Stripe API (Test Mode) |
| AI Chatbot | Google Gemini API |
| Train Data | RapidAPI - Indian Railways API |
| Email | JavaMail (Gmail SMTP) |
| PDF | iText PDF Library |

---

## 🚀 Getting Started

### Prerequisites
- Java 17 or higher
- Apache Tomcat 10.1
- MySQL 8.0
- Maven
- Eclipse IDE (recommended)

### Installation

**1. Clone the repository**
```bash
git clone https://github.com/vardhan1564/IRCTC_Clone.git
```

**2. Create MySQL Database**
```sql
CREATE DATABASE irctc;
```
Import the SQL schema file from:
