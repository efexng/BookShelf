# BookShelf

A simple **Express.js + EJS** web application for managing books and authors.
This project follows a classic **MVC (Model–View–Controller)** structure and was built as a learning/demo project.

---

## 🧠 Project Overview

BookShelf is a server-side rendered Node.js application that allows users to:

* View a homepage with recent books
* Manage books and authors (CRUD functionality)
* Render dynamic pages using EJS templates
* Serve static assets (CSS, images)

> ⚠️ **Note:** The project was originally designed to use MongoDB (via Mongoose). For preview/UI purposes, database functionality can be disabled or mocked.

---

## 🛠️ Tech Stack

* **Language:** JavaScript (Node.js)
* **Framework:** Express.js
* **Templating Engine:** EJS
* **Layout Engine:** express-ejs-layouts
* **Middleware:**

  * body-parser
  * method-override
* **Dev Tools:**

  * nodemon

---

## 📁 Project Structure

```text
githubpro/
├── server.js
├── package.json
├── routes/
│   ├── index.js
│   ├── books.js
│   └── authors.js
├── views/
│   ├── layouts/
│   ├── books/
│   └── index.ejs
├── public/
│   └── css/
└── models/   (MongoDB models – optional)
```

---

## 🚀 Getting Started

### 1️⃣ Install dependencies

```bash
npm install
```

---

### 2️⃣ Run the app (development mode)

```bash
npm run devStart
```

The app will start at:

```
http://localhost:3000
```

---

## 🧪 Running Without a Database

To preview the UI without MongoDB:

* Disable database-dependent routes (`/books`, `/authors`)
* Use a simplified `index.js` route that renders static or mock data

This allows you to view layouts, styling, and page structure without setup complexity.

---

## 🗄️ Database (Optional)

Originally designed to work with:

* **MongoDB**
* **Mongoose (ODM)**

If re-enabled, the app supports full CRUD operations for books and authors.

---

## 🎯 Purpose

This project is ideal for:

* Learning Express.js fundamentals
* Understanding MVC architecture in Node.js
* Practicing server-side rendering with EJS
* Building a portfolio demo project

---

## 📌 Future Improvements

* Re-enable MongoDB with environment-based config
* Add authentication
* Improve UI/UX
* Convert to API + frontend framework (React/Vue)

---

## 📄 License

ISC

---

## ✨ Author

Built as a learning/demo project.
