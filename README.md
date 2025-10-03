# Ecommerce Website

**Repository:** `mansi-katiyar/Ecommerce-Website-`

## 📌 Overview
This is a modern, responsive **E-commerce web application** built by **Mansi Katiyar**.  
It follows a **full-stack architecture** with separate `client` (frontend) and `server` (backend) folders.

The project showcases:
- Frontend development (React, UI/UX, responsive design)
- Backend REST APIs (Node.js, Express.js)
- Authentication & Authorization
- Product management, shopping cart, and checkout flow

---

## ✨ Features
- 🛍️ Product listing and detail pages  
- 🛒 Shopping cart with checkout process  
- 🔑 User authentication (login / signup)  
- 🛠️ Admin dashboard for product CRUD  
- 📦 Order history for users  
- 🌐 RESTful APIs for smooth integration  

---

## 🛠️ Tech Stack
- **Frontend:** React.js, HTML, CSS, JavaScript  
- **Styling:** TailwindCSS / Bootstrap  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB / MySQL  
- **Authentication:** JWT  
- **Version Control:** Git & GitHub  

---

## 📂 Repository Structure
├─ client/ # Frontend (React)

│ ├─ public/

│ └─ src/

│ ├─ components/

│ ├─ pages/

│ ├─ services/

│ └─ App.jsx

│

├─ server/ # Backend (Node + Express)

│ ├─ controllers/

│ ├─ models/

│ ├─ routes/

│ └─ app.js

│

├─ .gitignore

└─ README.md
## ⚡ Installation & Setup
1. Clone the repository
```bash
git clone https://github.com/mansi-katiyar/Ecommerce-Website-.git
cd Ecommerce-Website-
cd Ecommerce-Website-
Setup Backend

cd server
npm install
# create .env file for DB and JWT_SECRET
npm run dev
Setup Frontend

cd ../client
npm install
npm start
👉 App will run on: http://localhost:3000

