# LEGO Sets Web Application

This project is a full-stack web application developed for the **WEB-322** course.  
It demonstrates server-side rendering, secure user authentication, and database-driven CRUD operations using modern web technologies.

The application allows users to browse LEGO sets and themes, while authenticated users can manage sets and view their login history.

---

## 🚀 Features

- Server-side rendered pages using **EJS**
- Secure user registration and login system
- Password hashing with **bcrypt**
- Session-based authentication
- Login history tracking (last 8 logins)
- Browse LEGO sets and filter by theme
- View individual LEGO set details
- Authenticated users can:
  - Add new LEGO sets
  - Edit existing LEGO sets
  - Delete LEGO sets
- Custom **404** and **500** error pages
- Styled with **Tailwind CSS** and **DaisyUI**

---

## 🛠️ Tech Stack

### Backend
- **Node.js**
- **Express.js**

### Databases
- **PostgreSQL** (LEGO sets & themes, via Sequelize)
- **MongoDB** (user authentication & login history, via Mongoose)

### Frontend
- **EJS** (Server-side templates)
- **Tailwind CSS**
- **DaisyUI**

### Authentication & Security
- **bcryptjs** – password hashing
- **client-sessions** – session management
- Environment variables with **dotenv**

---


