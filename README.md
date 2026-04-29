# Item Manager (MERN Stack)

A complete MERN (MongoDB, Express, React, Node.js) Stack application for managing items with a custom `Material Type` field. This project was developed as part of a Lab Test to demonstrate full-stack enhancement, API deployment, and frontend hosting capabilities.

## 🚀 Live Demo

- **Frontend (Vercel):** [https://frontend-sithmi.vercel.app](https://frontend-sithmi.vercel.app)
- **Backend API (Render):** [https://item-manager-backend-lym8.onrender.com](https://item-manager-backend-lym8.onrender.com)

## ✨ Features

- **Full CRUD Operations:** Add, View, Edit, and Delete items.
- **Custom Data Fields:** Extended standard item data to include a custom `Material Type` field across the database, API, and UI.
- **Responsive UI:** Clean, intuitive, and responsive frontend built with React.
- **Separation of Concerns:** Clearly separated backend and frontend architectures in a monorepo setup.

## 🛠️ Tech Stack

- **Frontend:** React, Vite, Axios, React Router DOM
- **Backend:** Node.js, Express.js, Mongoose
- **Database:** MongoDB Atlas
- **Deployment:** Vercel (Frontend), Render (Backend)

## 💻 Running Locally

### 1. Backend Setup
```bash
cd backend
npm install
```
Create a `.env` file in the `/backend` directory:
```env
PORT=5001
MONGO_URI=your_mongodb_connection_string
```
Start the backend server:
```bash
npm run dev
```

### 2. Frontend Setup
```bash
cd frontend
npm install
```
Start the frontend development server:
```bash
npm run dev
```
The application will be available at `http://localhost:5173`.

## 📦 Deployment Information
- The backend was successfully deployed to **Render**, with environment variables securely configured to connect to a MongoDB Atlas cluster.
- The frontend was deployed using **Vercel** and connects to the Render API seamlessly.
