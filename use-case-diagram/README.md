# Airbnb Clone – Use Case Diagram

## 🎯 Objective
This diagram visualizes the **main system interactions** between users (actors) and the Airbnb backend system.  
It highlights how different types of users and external services interact with the core functionalities of the platform.

---

## 🧩 Key Actors

| Actor | Description |
|--------|-------------|
| **Guest** | A user who searches for, books, and reviews properties. |
| **Host** | A user who lists and manages properties on the platform. |
| **Admin** | The system administrator who manages users, listings, and transactions. |
| **Payment Gateway** | External service for processing secure payments (e.g., Stripe, PayPal). |
| **Notification Service** | Handles email and in-app notifications for users. |

---

## ⚙️ Use Cases

| Category | Use Cases |
|-----------|------------|
| **Guest** | Register/Login, Search Property, View Property Details, Book Property, Make Payment, Cancel Booking, Leave Review, Receive Notifications |
| **Host** | Register/Login, Add/Edit/Delete Property, Manage Bookings, Respond to Reviews, Receive Notifications |
| **Admin** | Manage Users, Monitor Payments, View Reports, Handle Disputes |
| **External Services** | Payment Gateway (processes payments), Notification Service (sends alerts) |

---

## 🖼️ Diagram Overview
The **Airbnb System** serves as the central boundary.  
- Guests and Hosts interact through booking, listing, and reviewing workflows.  
- The Admin oversees the system and manages key entities.  
- Payment Gateway and Notification Service act as external integrations supporting transactions and communications.

---


