# # BookShelf

A **server-side rendered Express.js + EJS** web application for managing books and authors.
This project follows a classic **MVC (Model–View–Controller)** structure and focuses on routing, templating, and UI rendering.

---

## 🧠 Project Overview

BookShelf is a Node.js web application that demonstrates:

* Server-side rendering with EJS
* Express routing and middleware
* Structured views with layouts and partials
* CRUD-style pages for books and authors (UI-focused)

This repository is primarily intended to **preview layout, navigation, and page structure** rather than persistence.

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
  * dotenv

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

## 🗄️ Data Storage

This project does **not require a database** to run.

All pages, routes, and layouts can be rendered without persistence. Any database-related files (such as models) are present only for structural completeness and learning purposes.

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
