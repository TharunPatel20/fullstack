# Login and Contact Management System

## 🚀 Project Overview

This is a secure, full-stack web application that enables users to register, log in, and manage their personal contacts. Each user has private access to their own data, ensuring information is isolated and secure.

---

## ✨ Key Features

- 🔐 **User Authentication**
  - Secure login functionality
  - Session persistence using local storage

- 📇 **Contact Management**
  - Add, view, and delete personal contacts
  - Each user can only access their own contacts

- 🔒 **Data Privacy**
  - Contacts are filtered based on the logged-in user
  - Backend authorization ensures users can't access each other’s data

---

## 🛠 Technologies Used

### 🔹 Frontend (React)
- **React** for building the user interface
- **React Router** for page navigation (Login, Dashboard, etc.)
- **Axios** for API communication
- **useContext / props** for state management
- **Local Storage** for maintaining session state

### 🔸 Backend (Spring Boot)
- **Spring Boot** for RESTful backend service
- **JPA & Hibernate** for ORM and database access
- **Entity Mapping**
  - `User` ↔️ `Contact` (OneToMany relationship)
- **Login API** for authentication
- Optional: **Spring Security** for enhanced authorization and access control

---

## 📁 Project Structure

### Frontend (React)
