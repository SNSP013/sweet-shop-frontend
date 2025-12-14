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

npm install
npm start


---

## 🔧 Environment Variables

Create a `.env` file in the root directory:

REACT_APP_API_URL=http://localhost:3000


---

## 📡 API Communication

The frontend uses a custom **Axios instance** that:  
- Automatically includes the JWT token in HTTP headers  
- Handles 401 errors globally  
- Redirects unauthorized users to the login page  

---

## 🖥️ Screens Overview

### 🔐 Login
- Authenticates the user  
- Stores JWT token in localStorage  

### 📊 Dashboard
- Displays total sweets count  
- Highlights low stock count  
- Shows user count (Admin only)  
- Lists recent sweets  
- Includes inventory preview  

### 🍭 Sweets Management
- List sweets  
- Create sweet  
- Edit sweet  
- Delete sweet (Admin only)  

### 📦 Inventory
- Purchase sweet  
- Restock sweet (Admin only)  

### 👥 Users (Admin Only)
- List users  
- Create user  
- Delete user  

---

## 📌 MY AI USAGE (Required Section)

### 🤖 Tools Used
- ChatGPT (GPT-5.1, GPT-4o)  
- GitHub Copilot  

---

## 🧠 Reflection — How AI Improved My Workflow

- Accelerated UI component creation.  
- Enabled high-quality UI without spending hours on CSS.  
- Helped structure the React app clearly and efficiently.  
- Significantly reduced debugging and development time.  
- Supported continuous learning of better coding patterns.  
- Functioned as both a **UI designer** and **React mentor**, leading to a polished and well-structured frontend.

---
## Website Page

- DashBoard (Landing Page)
<img width="1280" height="697" alt="image" src="https://github.com/user-attachments/assets/a57b605c-a70e-49e0-97cd-125dc3c9c5ed" />

<img width="1280" height="697" alt="image" src="https://github.com/user-attachments/assets/034491cf-d101-49af-94e0-7310a0330d85" />

- Sweets Page

<img width="1280" height="694" alt="image" src="https://github.com/user-attachments/assets/a9709fcf-ceaf-4f20-bef2-816ad04e7e21" />

- Add Sweet
<img width="1280" height="688" alt="image" src="https://github.com/user-attachments/assets/bed7422e-6aef-4462-9dec-53f97ad07c5a" />

- Inventory Page
<img width="1280" height="691" alt="image" src="https://github.com/user-attachments/assets/f29a9757-d1b7-428a-82c8-17b12611fa8d" />

- Users Page
<img width="1280" height="696" alt="image" src="https://github.com/user-attachments/assets/abe669da-cbbf-4302-8891-ffbcc9bf67b4" />

