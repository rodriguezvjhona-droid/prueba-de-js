Listo, te hice un **README profesional en inglés** basado en tu proyecto 👇 (ya listo para pegar en tu repo):

---

# 🚀 Workspace Reservation System SPA

## 📌 Overview

This project is a **Single Page Application (SPA)** built with modern frontend technologies. It simulates a workspace reservation system where users can authenticate, navigate protected routes, and manage reservations using a mock API.

The application is designed to demonstrate key frontend development concepts such as routing, authentication, role management, and API consumption.

---

## 🎯 Features

* 🔐 User authentication (Login / Logout)
* 🧭 SPA routing (no page reloads)
* 🛡️ Protected routes
* 👥 Role-based access (Admin / User)
* 💾 Session persistence with LocalStorage
* 🔄 API consumption using JSON Server
* 📦 Modular architecture
* 🎨 Responsive UI with TailwindCSS
* ⚠️ Custom 404 page

---

## 👤 User Roles

### 🛠️ Admin

* View all reservations
* Create, edit, and delete reservations
* Approve or reject reservations
* Manage workspace data
* Access admin modules

### 🙋 User

* View available workspaces
* Create reservations
* View their own reservations
* Edit pending reservations
* Cancel reservations

---

## 🧱 Tech Stack

* **JavaScript (ES6+)**
* **Vite**
* **TailwindCSS**
* **JSON Server**
* **Concurrently**
* **HTML5 & CSS3**

---

## 📁 Project Structure

```
src
├── assets
├── components
│   └── Sidebar.js
├── controllers
│   └── login.controller.js
├── router
│   └── router.js
├── views
│   ├── loginView.js
│   ├── homeView.js
│   └── notFound.js
├── utils.js
├── main.js
└── style.css
```

---

## 🧠 Architecture Explanation

### Components

Reusable UI elements like the Sidebar.

### Controllers

Handle business logic and events (e.g., login logic).

### Views

UI screens rendered dynamically (Login, Home, 404).

### Router

Manages navigation, route protection, and rendering.

### Utils

Helper functions for session management and authentication.

---

## 🌐 Mock API (JSON Server)

Example admin user:

```json
{
  "id": 1,
  "email": "admin@test.com",
  "password": "123456",
  "role": "admin"
}
```

Example normal user:

```json
{
  "id": 2,
  "email": "user@test.com",
  "password": "123456",
  "role": "user"
}
```

---

## ⚙️ Installation

Install dependencies:

```bash
npm install
```

---

## ▶️ Run the Project

```bash
npm run dev
```

This will start:

* Vite (frontend)
* JSON Server (mock backend)

---

## 🔑 Test Credentials

**Admin**

```
admin@test.com
123456
```

**User**

```
user@test.com
123456
```

---

## 📌 Available Scripts

```json
"scripts": {
  "dev": "concurrently \"vite\" \"json-server --watch db.json --port 3001\"",
  "build": "vite build",
  "preview": "vite preview"
}
```

---

## 🚧 Pending Features

* CRUD for reservations
* CRUD for workspaces
* Advanced route guards
* Role-based permissions
* Admin dashboard
* Statistics and analytics
* Filters and search
* Notifications system
* Business rules implementation

---

## 📄 License

This project is for educational purposes.

---

