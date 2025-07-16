# 🚀 URL Shortener – Daphnis Labs Internship Project

This is a **URL Shortener web application** built as part of my internship assessment at **Daphnis Labs**. It enables users to shorten long URLs, track their usage analytics, and view click statistics in a simple, responsive interface.

---

## ✨ **Features**

- 🌐 Shorten any valid long URL to a unique short code.
- 📊 View analytics dashboard with:
  - Total URLs created
  - Total clicks
  - Most popular link
  - Recent click activity chart
- 🔗 Detailed stats for each shortened URL including click history.
- ⚡ Responsive UI designed with **Tailwind CSS**.
- 🔧 Simulated backend logic with in-memory data (pure frontend implementation) for demo.

---

## 🛠️ **Tech Stack**

- **Frontend:** HTML5, CSS3 (Tailwind CSS), JavaScript (Vanilla)
- **Backend (current backend integration placeholder):** Node.js, Express.js, MongoDB, Mongoose (For database storage if integrated fully)
- **View Engine:** EJS (in server rendering implementation)

---

## 📂 **Project Structure**

url-shortener/
┣ models/
┃ ┗ shortUrl.js # Mongoose model schema
┣ views/
┃ ┗ index.ejs # Server-rendered frontend template
┣ public/
┃ ┗ index.html # Current Tailwind + JS frontend (if separated)
┣ server.js # Express server entry point
┣ package.json
┗ README.md


- **Server will start on:
http://localhost:5000
