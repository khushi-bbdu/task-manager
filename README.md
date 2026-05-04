# 🚀 Task Manager (Full Stack Web App)

A full-stack Task Management application that allows teams to create projects, assign tasks, and track progress with role-based access control.

This project demonstrates real-world application architecture including authentication, REST APIs, and database integration.

---

## ✨ Key Features

* 🔐 **Authentication System**

  * User Signup & Login
  * Secure JWT-based authentication

* 👥 **Role-Based Access Control**

  * Admin: Manage users & tasks
  * Member: View & update assigned tasks

* 📋 **Task Management**

  * Create, assign, update, delete tasks
  * Task status tracking (Pending / In Progress / Completed)

* 📊 **Dashboard**

  * Overview of tasks
  * Status-based filtering

* 🔍 **Search & Filtering** *(if added, keep — otherwise remove)*

---

## 🛠️ Tech Stack

### Frontend

* React (Vite)
* Tailwind CSS

### Backend

* Node.js
* Express.js

### Database

* MongoDB (Atlas)

### Other Tools

* JWT Authentication
* REST APIs

---

## 📁 Project Structure

task-manager/
├── client/        # Frontend (React)
├── server/        # Backend (Node + Express)
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   └── utils/
├── README.md

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

git clone https://github.com/khushi-bbdu/task-manager.git

cd task-manager

---

### 2️⃣ Setup Backend

cd server
npm install

Create `.env` file:

MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
PORT=5000

Run backend:

npm run dev

---

### 3️⃣ Setup Frontend

cd client
npm install

Run frontend:

npm start

---

## 🌐 Live Demo

🔗 (Add your Railway deployment link here)

---

## 📸 Screenshots

(Add screenshots of your app here for better presentation)

---

## 🚧 Future Improvements

* 🔔 Task reminders / notifications
* 🌙 Dark mode UI
* 📱 Mobile responsiveness improvements
* 📊 Advanced analytics dashboard

---

## 🙌 Learning & Contribution

This project was built as part of a learning process and enhanced with additional improvements to understand full-stack development concepts including:

* API design
* Authentication
* Database integration
* Deployment

---

## 👩‍💻 Author

**Khushi Tripathi**
GitHub: https://github.com/khushi-bbdu

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
