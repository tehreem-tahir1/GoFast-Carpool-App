---

# 🚗 GoFAST – Carpooling App for FAST NUCES Students

GoFAST is a MERN stack-based web application designed to help FAST NUCES students coordinate carpools efficiently. Built as part of our **Web Engineering course**, the platform reduces commute costs, promotes eco-friendly travel, and provides a safe, student-only carpooling system using verified FAST university emails.

---

## 📌 Project Overview

GoFAST connects FAST NUCES students who share similar routes, making daily commuting more affordable, sustainable, and convenient. Access is restricted to FAST email accounts to maintain trust, safety, and community exclusivity.

---

## 🌍 Introduction & Background

Carpooling saves fuel, reduces traffic, and promotes a greener environment. While ride-hailing apps like InDrive and Yango exist, they do not cater to students' campus-specific needs.
**GoFAST fills this gap** by offering a secure, reliable, university-focused ride-sharing solution.

---

## ❗ Problem Statement

FAST NUCES students face:

* High travel costs
* Limited transportation options
* No centralized system to manage carpools

GoFAST solves these problems by providing a **feature-rich, student-exclusive carpooling platform**.

---

## 🚀 Core Features

### 🔐 1. User Authentication

* Sign up using a **FAST email (@nu.edu.pk)**
* Email verification
* Password reset
* JWT-secured login
* User profile includes:

  * Name
  * Department
  * Batch
  * Contact Info

---

### 🚗 2. Carpool Post System

Users can create and browse ride posts with:

* Pickup & drop-off
* Departure time
* Seats available
* Ride preferences (e.g., female-only)

---

### 🔎 3. Search & Filter System

Search rides based on:

* Route
* Time
* Gender preference
* Department
* Batch
* (Optional) Map-based search

---

### 📩 4. Booking & Requests

* Send booking requests
* Accept/Decline system for ride owners
* Real-time confirmation alerts

---

### ⭐ 5. Reviews & Ratings

* Rate rides (1–5 stars)
* Write detailed feedback
* View past ratings

---

## ➕ Additional Features

### 💬 Real-Time Messaging

* Instant chat via WebSockets
* Live notifications

### 📍 Saved Routes & Ride History

* Save frequent routes
* View complete ride history

### 📡 Live Location Sharing

* Optional live GPS sharing

### 🌙 Dark Mode & UI Customization

* Light & Dark themes
* Clean, responsive UI (Tailwind CSS)

---

## 🛠️ Tech Stack (MERN)

### **Frontend**

* React.js
* React Router
* Tailwind CSS

### **Backend**

* Node.js
* Express.js
* JWT Auth
* WebSockets

### **Database**

* MongoDB

### **Email Services**

* Nodemailer (verification & recovery)
---

## 🎯 Project Outcomes

* End-to-end carpool system for FAST students
* Secure authentication with email verification
* Real-time chat and ride coordination
* User ratings and feedback
* Modern UI with customization
* Exclusively designed for FAST NUCES

---

## 📌 Completeness Criteria

* Verified sign-up and profile creation
* Carpool post creation & filtering
* Functional booking & messaging
* Ratings system implemented
* Live location sharing working
* App deployed and usable by students

---

## 🔗 Live Preview

Project Link: **[https://lnkd.in/dvp4CjME](https://lnkd.in/dvp4CjME)**

---

## 📘 Conclusion

GoFAST enhances daily commuting for FAST NUCES students by enabling safe, efficient, and eco-friendly ride-sharing. It promotes community connectivity and sustainability through a trusted, student-only platform.

---

## ▶️ How to Run the Project

From the main folder:

```bash
npm run start
```
