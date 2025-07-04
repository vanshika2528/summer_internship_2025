# 💼 Summer Internship 2025

This repository contains the work I completed during my *6th-semester summer internship. The project is a **client payment and installment tracking app* built using *Flutter* for the frontend and *PHP/MySQL* for the backend. 

---

## 🚀 Tech Stack

- *Frontend:* Flutter (Dart)
- *Backend:* PHP (XAMPP)
- *Database:* MySQL

---

## 📅 Weekly Breakdown

### 📌 Week 1 – Firebase Authentication & Dashboard UI
- Login & Signup with Firebase
- Forgot Password using sendPasswordResetEmail()
- Google Sign-In Integration
- Home Dashboard with:
  - Summary Cards: Clients, Transactions, Received, Outstanding
  - Quick Actions: Add Client, Payment, Installment
  - Recent Activity List

---

### 📌 Week 2 – XAMPP Setup & Backend APIs (Clients/Payments)
- Installed and configured XAMPP
- Created MySQL database
- Developed PHP endpoints for:
  - create.php: Add client with validation
  - delete.php: Delete client securely
  - Payment table with API to add/view payments

---

### 📌 Week 3 – SQL, PHP Basics & Auth Backend
- Practiced basic SQL: SELECT, INSERT, UPDATE, DELETE
- Created flutter_auth and cash_in_out databases
- Built backend login/signup APIs using PHP & MySQL
- Used Bcrypt for password hashing
- Connected Flutter to PHP via HTTP requests

---

### 📌 Week 4 – Clients Table & Home UI Integration
- Finalized schema with foreign keys
- Created transactions table with types (Got/Gave)
- Developed Add Client UI in Flutter
- Validated form inputs and connected to API
- Added Dashboard logic: Total Balance, You Will Get/Give
- Altered clients table to include balance column

---

### 📌 Week 5 – Add Payment Module
- Created payments table
- Developed Add Payment UI:
  - Dropdown for client selection
  - Validation (amount, date)
  - UI Feedback using Snackbars
- Used http.post() to insert payment
- Real-time UI updates using setState()

---

### 📌 Week 6 – App Branding & Theming
- Changed app icon and label
- Added custom splash screen
- Implemented Light/Dark Theme toggle
- Used ThemeMode & ValueNotifier for dynamic switch

---

### 📌 Week 7 – Installment Plan Feature
- Tables: installment_plans and installments
- Backend APIs for creating and fetching plans
- Flutter UI:
  - Add Installment Plan form
  - Monthly installment generation
  - Installment List view with payment status
- Modified Payment Page to:
  - Associate payments with installments
  - Show pending months in dropdown
