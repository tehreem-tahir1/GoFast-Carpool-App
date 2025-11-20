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
- High travel costs  
- Limited transportation options  
- No centralized system to manage carpools  

GoFAST solves these problems by providing a **feature-rich, student-exclusive carpooling platform**.

---

## 🚀 Core Features

### 🔐 1. User Authentication
- Sign up using a **FAST email (@nu.edu.pk)**
- Email verification required
- Password reset via email
- JWT-secured login sessions
- User profile includes:
  - Name  
  - Department  
  - Batch  
  - Contact Info  

---

### 🚗 2. Carpool Post System
Users can create and browse ride posts with:
- Pickup & drop-off points  
- Departure time  
- Available seats  
- Ride preferences (e.g., female-only)  
- Posts visible to relevant students  

---

### 🔎 3. Search & Filter System
Search rides based on:
- Route  
- Departure time  
- Gender preference  
- Department & batch  
- (Optional) Map-based visual route selection  

---

### 📩 4. Booking & Requests
- Send requests to ride creators  
- Accept/Decline system for ride owners  
- Real-time confirmation alerts  

---

### ⭐ 5. Reviews & Ratings
- Rate rides (1–5 stars)  
- Leave detailed feedback  
- View ride history and past ratings  

---

## ➕ Additional Features

### 💬 Real-Time Messaging
- Instant chat using **WebSockets**
- Message notifications

### 📍 Saved Routes & Ride History
- Save frequent routes  
- Access complete ride history  

### 📡 Live Location Sharing
- Optional real-time location sharing for safety during rides  

### 🌙 Dark Mode & UI Customization
- Light/Dark theme toggle  
- Smooth, responsive UI with Tailwind CSS  

---

## 🛠️ Tech Stack (MERN)

### **Frontend**
- React.js  
- React Router  
- Tailwind CSS  

### **Backend**
- Node.js  
- Express.js  
- JWT Authentication  
- WebSockets for real-time features  

### **Database**
- MongoDB  

### **Email Services**
- Nodemailer (email verification & password recovery)

---

## ✅ Completeness Criteria
- Verified sign-up & profile creation  
- Carpool post creation system  
- Filtering and route-based search  
- Booking and real-time messaging  
- Ratings and reviews  
- Live location sharing  
- Fully deployed and functional for FAST NUCES students  

---

## ▶️ How to Run the Project

From the main folder:

```bash
npm run start
----
🎯 Project Outcomes

-End-to-end carpooling system for FAST students
-Secure authentication with email verification
-Real-time chat and ride coordination
-User feedback system with ratings
-Modern UI and theme customization
-Designed exclusively for the FAST NUCES community
---------

## Completeness Criteria

- Verified sign-up and profile creation
- Carpool post creation and filtering
- Booking and messaging working smoothly
- Review system in place
- Real-time location sharing
- App deployed and usable by students
------
🔗 Live Preview

Project Link: https://lnkd.in/dvp4CjME
---

## Conclusion

GoFAST is designed to improve the daily commute for FAST NUCES students by making it easier to share rides. With a focus on trust, convenience, and sustainability, it creates a connected and eco-conscious student community.

---
