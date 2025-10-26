# Airbnb Clone – Data Flow Diagram (DFD)

## 🎯 Objective
This document illustrates the flow of data across the main backend processes in the **Airbnb Clone** system.

---

## 🗺️ Components
- **External Entities:** Guest, Host, Admin, Payment Gateway  
- **Processes:** User Authentication, Property Management, Booking Management, Payment Processing, Notification Service  
- **Data Stores:** Users DB, Properties DB, Bookings DB, Payments DB, Notifications DB  

---

## 🔄 Data Flow Overview
1. **Guests** and **Hosts** interact with the system through authentication and property management modules.
2. **Bookings** trigger **payments** via an external payment gateway.
3. Successful transactions update **bookings** and send **notifications** to users.
4. **Admins** oversee all stored data and transactions for maintenance and support.

---

## 🖼️ Diagram
The diagram below (data-flow.png) represents the Level 1 DFD for the Airbnb backend system.

---

**File Structure:**
