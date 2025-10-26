# Airbnb Clone Backend – Requirements Specification

## 🧩 Overview
This document outlines the **functional** and **technical requirements** for three key backend modules of the Airbnb Clone project:
1. User Authentication
2. Property Management
3. Booking System

Each section includes API endpoints, input/output structures, validation rules, and performance expectations.

---

## 1. 🧍 User Authentication

### 1.1 Objective
Provide secure user registration, login, and account management.

### 1.2 Functional Requirements
- Users can register using an email and password.
- Users can log in and receive an authentication token (JWT or session).
- Passwords must be hashed and securely stored.
- Authenticated users can update their profile details.

### 1.3 API Endpoints

| Method | Endpoint | Description | Auth Required |
|--------|-----------|--------------|---------------|
| POST | `/api/auth/register` | Register a new user | No |
| POST | `/api/auth/login` | Log in and obtain token | No |
| GET | `/api/auth/profile` | Retrieve user profile | Yes |
| PUT | `/api/auth/profile` | Update user details | Yes |

### 1.4 Input / Output Specifications

#### POST `/api/auth/register`
**Input (JSON):**
```json
{
  "username": "johndoe",
  "email": "john@example.com",
  "password": "Password123!"
}
