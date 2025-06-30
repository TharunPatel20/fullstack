# 🔐 Login & Contact Management | 👤 User Registration | ✅ Task Tracker (Spring Boot + React)

A collection of 3 full-stack web applications built using **React (frontend)** and **Spring Boot (backend)**. Each application demonstrates essential concepts in authentication, CRUD operations, form validation, and user-specific data handling.

---

## 📁 Project Modules

### 1. 🔐 Login and Contact Management System

#### 📌 Overview:
A secure system that allows users to **log in** and **manage personal contacts**. All contacts are private and tied to the authenticated user.

#### ✅ Features:
- User login and session management
- Add, view, and delete personal contacts
- Contact data is private per user

#### 🧰 Tech Stack:
- **Frontend (React):**
  - React Router for routing between login and dashboard
  - useContext/localStorage for session state
  - Axios for secure API calls

- **Backend (Spring Boot):**
  - `User` & `Contact` entities (OneToMany)
  - User authentication API
  - Contact filtering by user
  - Optional: Role-based authorization using Spring Security

---

### 2. 👤 User Registration and Profile Viewer

#### 📌 Overview:
Allows users to **register**, view their profiles, and gives **admins** the ability to view all registered users.

#### ✅ Features:
- User registration form with validation
- View profile details
- Admin interface to list all users

#### 🧰 Tech Stack:
- **Frontend (React):**
  - Form validation and error display
  - Dynamic routing (React Router)
  - Tabular user list rendering

- **Backend (Spring Boot):**
  - `User` entity with fields: name, email, password
  - APIs for registration and profile fetch
  - Input validation using `@Email`, `@NotBlank`
  - Optional: Password encryption with `BCrypt`

---

### 3. ✅ Task Management System with Status Tracking

#### 📌 Overview:
A productivity app for users to **create**, **update**, and **track tasks** through different stages (Pending → In Progress → Completed).

#### ✅ Features:
- Add tasks with title & description
- Update task status
- Delete tasks
- Filter tasks by status

#### 🧰 Tech Stack:
- **Frontend (React):**
  - `useState` / `useEffect` for local state and effects
  - Controlled inputs for task creation/update
  - Dropdowns for status selection
  - Axios for REST calls

- **Backend (Spring Boot):**
  - `Task` entity with title, description, status (Enum)
  - Full CRUD REST API
  - H2/MySQL database support
  - Input validation with `@Valid`
  - Global exception handling
  
---
