

````markdown
# CampusTrackr 🎓

CampusTrackr is a full-stack college data management system built with the MERN stack (MongoDB, Express, React, Node.js).

> This repo includes both the frontend and backend directories.

---

## 🔧 Project Setup

### 1. Clone the Repository

```bash
git clone https://github.com/samhitamahe/CampusTrackr.git
cd CampusTrackr
````

---

## 📂 Folder Structure

* `api-main/` → Node.js + Express Backend (REST API)
* `frontend/` → React Frontend with TailwindCSS

---

## 🚀 Quick Start Guide

### Backend Setup (`api-main`)

```bash
cd api-main
npm install
```

Create a `.env` file and add your MongoDB URI:

```
DATABASE_URI=mongodb+srv://username:password@cluster.mongodb.net/campustrackr
```

Then start the server:

```bash
npm run dev
```

During development, allow requests without headers by updating:

```js
// config/corsOptions.js
if (
  allowedOrigins.indexOf(origin) !== -1 
  || !origin // Enable this line in development
)
```

---

### Frontend Setup (`frontend`)

```bash
cd frontend
npm install
npm start
```

To change the backend server address, edit:

```js
// src/config/api/axios.js
baseURL: "http://localhost:3500";
```

---

## 👥 Roles & Logins

### 🔑 Teacher (Staff)

* **Username:** Delphine
* **Password:** Delphine123
* Can: Add/Edit Notes, Attendance, Internals, Schedule

### 🔑 HOD

* **Username:** samm
* **Password:** samm
* Can: Do everything a teacher can + Approve Teachers, Add Papers

### 🔑 Student

* **Username:** akshi
* **Password:** akshi
* Or register a new student with any first name
* Can: View Notes, Attendance, Internal Marks, Join/Leave Papers

---

## 🛠️ Tech Stack

**Frontend:**

* React
* TailwindCSS
* React Router, React Icons, React Toastify
* Axios

**Backend:**

* Node.js
* Express.js
* MongoDB + Mongoose

---

## 📞 Contact

Feel free to raise issues or contact for feedback via LinkedIn / Email.
Please be kind and constructive. 😊

---
