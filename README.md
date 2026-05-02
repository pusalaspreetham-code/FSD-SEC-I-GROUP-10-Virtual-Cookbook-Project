# 🍳 CookBook – Your Virtual Kitchen Assistant

## 📌 Project Overview

CookBook is a web-based application that helps users discover, create, and manage recipes easily.  
It allows users to search recipes based on ingredients or cuisine, save favorites, and share ideas through a community section.

This project is built using the **MERN Stack (MongoDB, Express, React, Node.js)** and demonstrates full-stack development concepts such as authentication, API integration, and data management.

---

## 🎯 Features

- 🔍 Search recipes by ingredients or cuisine  
- 📖 View detailed recipe instructions (ingredients, steps, cooking time)  
- ❤️ Save and manage favorite recipes  
- ➕ Create and manage custom recipes  
- 🧑‍🤝‍🧑 Community interaction (posts & likes)  
- 🔐 Secure login & registration using JWT  

---

## 📁 Project Files 
project/
│
├── frontend/      # React frontend
├── backend/       # Node.js backend
└── README.md


---

## 📦 How to Unzip the Project

1. Download the file **Project_file_FSD.zip**
2. Right-click and select **Extract Here**  
   (or use WinRAR / 7-Zip)
3. After extraction, the project structure will be:
frontend/
backend/


---

## ⚙️ How to Run the Project

### 🔹 Step 1: Open Project in VS Code

Open both folders:
- frontend  
- backend  

---

### 🔹 Step 2: Install Dependencies

#### Frontend:
```bash
cd frontend
npm install
npm install express mongoose dotenv cors bcrypt jsonwebtoken
npm run dev

#### Backend:
```bash
cd backend
npm install
npm install axios react-router-dom
npm install emailjs-com
node server.js
