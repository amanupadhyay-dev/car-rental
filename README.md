# 🚗 Car Rental Web App (Frontend)

A modern and responsive car rental application frontend built using **React.js**, **Tailwind CSS**, and **Vite**. Users can explore available cars, select rental dates, and browse based on category or pricing.

## 🌐 Live Demo (Frontend)
[🔗 Visit Car Rental Frontend] ( https://car-rental-ltk9pomxt-aman-uadhyays-projects.vercel.app/ )


## 🔁 Technologies Used

| Layer     | Tech Stack                          |
|-----------|-------------------------------------|
| Frontend  | React.js, Tailwind CSS, Vite        |
| Backend   | Node.js, Express.js, MongoDB Atlas  |
| Hosting   | Vercel (frontend), Render (backend) |

## 📁 Folder Structure

car-rental/
├── client/ # React Frontend (Vite + Tailwind)
│ ├── public/ # Static assets
│ ├── src/
│ │ ├── assets/ # Images, icons, etc.
│ │ ├── components/ # Reusable React components
│ │ ├── pages/ # Page-wise components
│ │ ├── routes/ # React Router files (if used)
│ │ ├── utils/ # Axios instance, helper functions
│ │ └── App.jsx # Root component
│ ├── index.html
│ └── vite.config.js
│
├── server/ # Node.js + Express Backend
│ ├── controllers/ # Route handler logic
│ ├── models/ # Mongoose DB Models
│ ├── routes/ # API route definitions
│ ├── middleware/ # Auth, error, validation, etc.
│ ├── config/ # MongoDB connection, env setup
│ ├── uploads/ # For storing image files (optional)
│ ├── .env # Environment variables
│ └── index.js # Server entry point
│
├── .gitignore
├── README.md


