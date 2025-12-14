✅ FRONTEND — FULL README.md (Ready to Paste)
# 🍬 Sweet Shop Frontend

Frontend for the Sweet Shop Management System built using **React**, **React Router**, **Axios**, and a completely custom modern UI with global CSS animations and transitions.

---

## 🚀 Features

- Login system with JWT
- Protected routes based on role (Admin/User)
- Dashboard with real-time metrics
- Modern UI with animations, shadows, and glassmorphism
- Sweets management (CRUD)
- Inventory management (Purchase / Restock)
- User management (Admin only)
- Global CSS theme for consistent styling

---

## 🛠️ Tech Stack

- **React**
- **React Router**
- **Axios**
- **jwt-decode**
- **Custom global CSS**

---

## 📦 Installation

```sh
npm install
npm start

🔧 Environment Variables

Create .env:

REACT_APP_API_URL=http://localhost:3000

📡 API Communication

The frontend uses an Axios instance that:

Automatically includes JWT token in headers

Handles 401 errors globally

Redirects unauthorized users to login

🖥️ Screens Overview
🔐 Login

Authenticates user

Stores JWT token

📊 Dashboard

Total sweets

Low stock count

User count (Admin)

Recent sweets

Inventory preview

🍭 Sweets Management

List sweets

Create sweet

Edit sweet

Delete sweet (Admin)

📦 Inventory

Purchase sweet

Restock sweet (Admin)

👥 Users (Admin Only)

List users

Create user

Delete user

📌 MY AI USAGE (Required Section)
🤖 Tools Used

ChatGPT (GPT-5.1, GPT-4o)

GitHub Copilot

🔧 How I Used AI
1. React Components

AI helped generate:

Login, Dashboard, Sweets pages

User & Inventory management pages

Navbar with dynamic role rendering

ProtectedRoute component logic

2. Axios Client

AI wrote:

Axios instance with interceptors

Token injection logic

Error handling middleware

3. Animations & CSS

AI designed:

Global CSS theme (Inter + Poppins fonts)

Glassmorphism navbar

Floating metric cards

Button micro-interactions

Smooth fade + slide animations

4. Bug Fixing

AI resolved:

Delete API failing due to missing token

Sweet Edit not loading due to wrong URL

Login errors caused by incorrect backend prefix

Slow re-renders & missing dependencies

5. UX Improvements

AI suggested:

Better layout spacing

Dashboard grid layout

Inventory color-coded statuses

🧠 Reflection — How AI Improved My Workflow

Accelerated UI component creation.

Enabled creation of high-quality UI without spending hours on CSS.

Helped structure React app cleanly.

Significantly reduced debugging time.

Allowed me to learn better coding patterns.

AI acted as both a UI designer and React mentor, helping deliver a polished frontend quickly.
