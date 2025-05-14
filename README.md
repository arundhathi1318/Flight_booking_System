# ✈️ Flight Booking System (Web-Based, MVC Architecture)

A fully responsive, web-based **Flight Booking System** built using the **Model-View-Controller (MVC)** architecture. This Java-based application enables users to search, book, and manage flight tickets online. It features role-based access control, secure authentication, and protection against common web vulnerabilities like SQL Injection and XSS.

---

## 🚀 Features

- Role-Based Access: Airline Admin, Airline Manager, Customer
- Seat Category Management: First Class, Business, Economy
- Seat Availability & Price Approval Workflow
- Secure Login with Tomcat Roles
- Flight Search Widget using AJAX
- SOAP Web Services Integration for Price & Seat Info
- Itinerary Generation and Email Confirmation
- SQL Injection & XSS Protection

---

## 🛠️ Technologies Used

### 💻 Frontend
- HTML, CSS, JavaScript
- jQuery, Bootstrap
- JavaServer Pages (JSPs)
- AJAX (Flight Search Widget)

### 🧠 Backend
- Java Servlets
- Java Models
- Microsoft Access Database

### 🔐 Security
- Tomcat Roles (Authentication & Authorization)
- SQL Injection and XSS Protection

### 🌐 Web Services
- SOAP for retrieving seat pricing and availability

---

## 👥 User Roles & Functionalities

### 👨‍✈️ Airline Admin
- Set and update seat prices
- Define features of seat classes (First, Business, Economy)
- Set total number of seats per flight

### 🧑‍💼 Airline Manager
- View and approve seat pricing or updates
- Only approved seats and prices are visible to customers

### 🧑‍💻 Customer
- Search flights by origin, destination, travel dates, and passengers
- Book available seats and confirm itinerary
- Make secure payment (simulated)
- Receive email confirmation with itinerary details

---

## 🔄 Booking Workflow

1. Admin sets and updates seat details.
2. Manager reviews and approves changes.
3. Customers search for available flights and book tickets.
4. Upon payment confirmation, the system updates available seats.
5. Email notification with itinerary is sent to the customer.

---

## 📂 Folder Structure

