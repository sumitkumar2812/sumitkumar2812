# 🏠 Property Rental Platform (MERN Stack)

A modern, full-stack real estate and property rental web application designed to seamlessly connect property owners and tenants. Users can browse listings, view detailed property information, manage their own listings, and securely handle authentication.

---

## 🌟 Key Features

* **Authentication & Authorization:** Secure user registration, password hashing using `bcryptjs`, and session control via JSON Web Tokens (JWT).
* **Interactive UI:** Responsive navbar, dynamic property search, grid/list view, and detailed individual property pages.
* **Property Management (CRUD):** Logged-in property hosts can create, edit, update, and delete their property listings.
* **Multi-Image Handling:** Support for multi-photo uploads per property listing with server-side storage and existing image cleanup.
* **Dashboard / My Properties:** Personalized view for hosts to manage active rental listings with smooth UI state updates.

---

## 🛠️ Tech Stack

### Frontend
* **React.js** — Component-driven UI development
* **Vite** — High-performance frontend build tool and development server
* **CSS / Tailwind CSS** — Responsive styling and layout

### Backend
* **Node.js** — Asynchronous runtime environment
* **Express.js** — RESTful API framework
* **MongoDB & Mongoose** — NoSQL database and Object Data Modeling (ODM)
* **JWT & Bcrypt.js** — Authentication and password security
#### TO SEE THE LIVE PROJECT PLEASE CLICK HERE --
#### https://property-rental-platform-front.vercel.app/
---

## 📁 Project Structure

```text
property-rental-app/
├── client/                # React Frontend (Powered by Vite)
│   ├── src/
│   │   ├── components/    # Reusable UI components (Navbar, Cards, Forms)
│   │   ├── pages/         # Page views (Home, Login, Signup, MyProperties)
│   │   └── App.jsx        # Main application component & routes
│   └── vite.config.js
│
└── server/                # Node.js + Express Backend
    ├── controllers/       # Business logic for auth & properties
    ├── models/            # Mongoose schemas (User, Property)
    ├── routes/            # API Endpoints
    └── server.js          # Entry point & DB connection

