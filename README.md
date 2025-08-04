# CampusTrackr

Here’s a clear and organized `README.md` file for your **CampusTrackr** project — split into two parts: **API (Backend)** and **Frontend**.

---

### ✅ Root `README.md` for CampusTrackr

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

* **Username:** Moriah
* **Password:** Moriah123
* Can: Do everything a teacher can + Approve Teachers, Add Papers

### 🔑 Student

* **Username:** Bret
* **Password:** Bret
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

## 🔜 Roadmap

* [ ] Add Admin Panel
* [ ] Cache & Paginate Queries
* [ ] Export Student Reports

---

## 📞 Contact

Feel free to raise issues or contact for feedback via LinkedIn / Email.
Please be kind and constructive. 😊

---

## 📄 License

MIT

---

## 🌐 Demo

Soon to be hosted on Render...

---

```

Let me know if you’d like:
- A more **developer-focused** vs **user-focused** version
- Separate READMEs inside `api-main/` and `frontend/`
- A deploy guide (Render/Netlify/Vercel)

I can customize it based on your goals for the project (e.g., demo for recruiters, open-source showcase, team project).
```
