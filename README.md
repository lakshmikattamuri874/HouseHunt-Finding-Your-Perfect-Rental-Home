# 🏠 House Rent App – MERN Stack

A full-stack House Rental Web Application built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**.

This platform allows renters to search and book properties, owners to list and manage properties, and admins to control and monitor the system.

---

# 📌 Introduction

The House Rent App is designed to simplify the process of finding and listing rental properties.

HouseHunt streamlines the real estate journey by providing a user-friendly platform that connects:

- Renters  
- Property Owners  
- Administrators  

It reduces the complexity of property searching, booking, and management.

---

# 🎯 Objectives

- Provide detailed and transparent property information  
- Simplify property search using advanced filters  
- Enable smooth booking and status tracking  
- Allow owners to manage property listings  
- Provide admin control for user and property approval  

---

# 🚀 Features

## 🔎 Advanced Property Search
- Filter by location  
- Filter by price range  
- Filter by bedrooms  
- Filter by amenities  
- View detailed property information  

## 🏘️ Property Listings
- High-quality property images  
- Property descriptions  
- Owner details  
- Availability status  

## 📅 Booking System
- Send booking requests  
- View booking history  
- Track booking status (Pending / Approved / Rejected)  

## 👥 Role-Based Access
- Renter  
- Owner  
- Admin  

## 🛡️ Admin Panel
- Approve owner accounts  
- Monitor users  
- Manage properties  
- Enforce system policies  

---

# 🧱 Technical Architecture

The application follows a **Client-Server Architecture**.

## 🖥️ Frontend
- React.js  
- Bootstrap  
- Material UI  
- Ant Design (Antd)  
- Axios  
- Moment.js  
- MDB React UI Kit  
- React Bootstrap  

## ⚙️ Backend
- Node.js  
- Express.js  
- MongoDB  
- Mongoose  
- JWT Authentication  
- bcryptjs  
- Multer  
- CORS  
- dotenv  
- Nodemon  

## 🗄️ Database
MongoDB stores:
- Users (Renter, Owner, Admin)  
- Properties  
- Bookings  

---

# 👤 User Roles & Responsibilities

## 🧑‍💼 Renter
- Register and login  
- View all properties  
- View property details  
- Send booking request  
- Check booking status  

## 🏠 Owner
- Get approval from admin  
- Add, edit, delete properties (CRUD)  
- Manage property availability  
- Approve or reject bookings  

## 🛡️ Admin
- Approve owner accounts  
- Monitor all users  
- Manage properties  
- Enforce policies  

---

# 📂 Project Structure

    house-rent/
    │
    ├── frontend/
    │   ├── components/
    │   ├── pages/
    │   ├── redux/
    │   ├── App.js
    │   └── package.json
    │
    ├── backend/
    │   ├── config/
    │   ├── models/
    │   ├── routes/
    │   ├── middleware/
    │   ├── server.js
    │   └── package.json
    │
    └── README.md

---

# ⚙️ Prerequisites

Make sure you have installed:

- Node.js  
- npm  
- MongoDB (Local or Atlas)  
- Git  
- VS Code or any IDE  

---

# 🛠️ Installation & Setup

## 1️⃣ Clone the Repository

    git clone https://github.com/awdhesh-student/house-rent.git
    cd house-rent

## 2️⃣ Install Dependencies

### Frontend

    cd frontend
    npm install

### Backend

    cd ../backend
    npm install

## 3️⃣ Setup Environment Variables

Create a `.env` file inside the backend folder and add:

    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_secret_key

## 4️⃣ Run the Application

### Start Backend

    cd backend
    npm start

### Start Frontend

    cd frontend
    npm start

The application will run at:

    http://localhost:3000

---

# 🔐 Authentication & Security

- JWT-based authentication  
- Password hashing using bcryptjs  
- Role-based access control  
- Protected API routes  

---

# 📸 Application Modules

- Register / Sign Up  
- Login  
- Property Listings  
- Property Details  
- Booking History  
- Admin Dashboard  

---

# 🎥 Project Demo

Demo Links:

- https://drive.google.com/file/d/1enBJk-X3-ScODu_FMvZRJinwFIDdngb1/view  
- https://drive.google.com/file/d/1beQU9Ba_8l-NcLFcU7CX7DLeG-Yk0BL0/view  

---

# 💻 Source Code

GitHub Repository:  
https://github.com/awdhesh-student/house-rent  

---

# 🔮 Future Enhancements

- Online payment integration  
- Real-time chat system  
- Email notifications  
- Ratings and reviews  
- Map integration  
- Cloud image storage  

---

# 📌 Conclusion

The House Rent App demonstrates a complete MERN stack implementation with authentication, role-based access control, CRUD operations, and booking management.

It provides a scalable foundation for building a real-world rental platform.
