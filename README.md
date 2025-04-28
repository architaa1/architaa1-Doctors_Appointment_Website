# 🩺 Doctor Appointment System

A full-stack MERN (MongoDB, Express, React, Node.js) web application that allows users to register, login, search for doctors, and book appointments. Doctors and Admins have separate dashboards to manage their schedules and view appointments.

## 🚀 Live Demo

Hosted on **Render**: https://archita-doctors-appointment-website.onrender.com

Demo Video Link : https://drive.google.com/file/d/1VLIU-fHRX6S3MIQnrayenmndHGMQwrbh/view?usp=drive_link

---

## 📌 Features

### 👤 User
- Register & Login (JWT Authentication)
- Book appointments with available doctors
- View booking history and appointment status
- View and manage notifications

### 🩺 Doctor
- Register & Await Approval
- Manage availability
- View appointment requests
- View and manage notifications

### 👨‍💼 Admin
- Approve or reject doctor registrations
- View all doctors & users
- View and manage notifications

---

## 🛠️ Tech Stack

| Frontend        | Backend          | Database | Other Tools     |
|----------------|------------------|----------|-----------------|
| React.js        | Express.js       | MongoDB  | Render (Hosting)|
| Bootstrap       | Node.js          | Mongoose | Dotenv, Morgan  |

---

## 📁 Project Structure
. ├── client # React frontend 

├── config # DB configuration 

├── controllers # Business logic 

├── models # MongoDB models 

├── routes # Express routes 

├── middleware # Authentication, admin check 

├── server.js # Entry point 

└── .env # Environment variables


---

## ⚙️ Setup Instructions

### 1. Clone the Repository

git clone https://github.com/architaa1/Doctors_Appointment_Website.git
cd Doctors_Appointment_Website

### 2. Install Dependencies
For Backend:
npm install

For Frontend:

cd client
npm install

### 3. Configure Environment Variables
Create a .env file in the root folder and add:

PORT=8080
NODE_MODE=development
MONGO_URL=your_mongo_connection_string
JWT_SECRET=your_jwt_secret_key

### 4. Run the App

# Backend
npm run server

# Frontend (in /client)
npm start

### 5. Build Frontend for Production

cd client
npm run build

🐞 Troubleshooting
Make sure the build folder exists before deploying.

If deploying on Render or similar platforms, ensure your client/build is not ignored in .gitignore.

📜 License
This project is licensed under the MIT License.

🙋‍♀️ Author
Made with ❤️ by Archita
Inspired from:- TechInfoYT




