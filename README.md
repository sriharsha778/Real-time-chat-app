# Real-time-chat-app

A **MERN** (MongoDB, Express, React, Node.js) based chat and forum application.

---

## 🔧 Project Structure

Real-time-chat-app   
├── backend/  
├── frontend/  
├── .gitignore  
├── README.md  
├── package.json  


## 🛠 Prerequisites

Before you begin, ensure you have the following installed:     

- [Node.js](https://nodejs.org/) (version 16 or later)  
- [Git](https://git-scm.com/)  

> ✅ **MongoDB** and **Cloudinary** do not require local installation — they are accessed via npm packages like `mongoose` and `cloudinary`, using credentials provided via `.env`.

---

## 🚀 Getting Started

### 1. Clone the Repository

git clone https://github.com/sriharsha778/Real-time-chat-app   
cd Real-time-chat-app  

---

### 2. Set Up the Backend

cd backend  
npm install  

### Create a `.env` file inside the `backend/` folder with the following content:  

MONGODB_URI=your_remote_mongodb_url  
PORT=5001    

JWT_SECRET=mysecretkey  
NODE_ENV=development    

CLOUDINARY_CLOUD_NAME=your_cloudinary_name  
CLOUDINARY_API_KEY=your_cloudinary_api_key  
CLOUDINARY_API_SECRET=your_cloudinary_api_secret_key  


#### Start the backend server:  

npm run dev  


---

### 3. Set Up the Frontend

cd ../frontend  
npm install  
npm run dev  

The frontend is built using **Vite** and styled with **TailwindCSS**.  

---

## ✨ Features

- 🔒 JWT Authentication for login/register
- 💬 Real-time chat system with Socket.IO
- 📝 Forum support with threaded posts/comments
- ⚡ Clean, modern UI built with React + TailwindCSS

---


## 🧪 Useful npm Packages

| Package         | Purpose                                |
|------------------|----------------------------------------|
| `mongoose`       | MongoDB ODM for schema + connections  |
| `cloudinary`     | Media storage and image upload service |
| `express`        | Backend framework (Node.js)            |
| `socket.io`      | Real-time WebSocket communication      |
| `jsonwebtoken`   | JWT-based authentication               |
| `react`, `vite`  | Frontend framework and build tool      |
| `tailwindcss`    | Utility-based CSS framework            |

---

## 📜 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## ✅ Optional Enhancements

Let us know if you'd like to include:

- 📄 `.env.example` – Boilerplate for teammates' environment setup
- 📑 API Documentation – Swagger or Postman collections
- 🚀 Deployment Guide – Steps to deploy on Render, Vercel, Railway, etc.
- 🖼️ Screenshots/GIFs – To showcase your UI and features

---

**Made with ❤️ by your team for the 2024-25 Mini Project**
