# 🔗 URL Shortener

> A lightweight and efficient **URL Shortener backend** built using **Node.js**, **Express**, and **MongoDB**.
> This API allows users to convert long URLs into compact, shareable links with instant redirection.

---

## 🌟 Overview

This project provides a **RESTful API** that shortens lengthy URLs and stores them in a **MongoDB** database. Each shortened URL is assigned a unique identifier and can be accessed to redirect users to the original link.

---

## 🚀 Features

* 🔒 **Shorten long URLs** into simple, easy-to-share short links
* 🔁 **Instant redirection** to the original URLs
* 💾 **MongoDB integration** for persistence and scalability
* ⚙️ **Environment configuration** with `dotenv`
* 🧩 **Hot reloading** with `nodemon` during development

---

## 🧮 Tech Stack

| Category  | Technologies Used   |
| --------- | ------------------- |
| Backend   | Node.js, Express.js |
| Database  | MongoDB             |
| Utilities | dotenv, nodemon     |

---

## ⚙️ Installation & Setup

> 💡 *Frontend and deployment integration instructions coming soon!*

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Arnav301/Url-Shortner.git
cd url-shortener
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Configure environment variables

Create a `.env` file in the root directory and add the following:

```bash
PORT=5000
MONGO_URI=your_mongodb_connection_string
BASE_URL=http://localhost:5000
```

### 4️⃣ Run the server

```bash
npm run dev
```

Your backend server will now be running with **nodemon** on the specified `PORT`.

---

## 📡 API Endpoints

| Method   | Endpoint       | Description                   |
| -------- | -------------- | ----------------------------- |
| **POST** | `/api/shorten` | Shortens a long URL           |
| **GET**  | `/:shortId`    | Redirects to the original URL |

### 📾 Example Request

**POST** `/api/shorten`

```json
{
  "longUrl": "https://www.example.com/very/long/link"
}
```

### 🥯 Example Response

```json
{
  "shortUrl": "http://localhost:5000/abc123",
  "originalUrl": "https://www.example.com/very/long/link"
}
```

---

## 🧠 Future Enhancements

* 🔐 **User authentication** and URL ownership
* 📊 **Click tracking & analytics dashboard**
* 🌐 **Frontend integration** using React.js
* ☁️ **Cloud deployment** on Render / Vercel
* 🧮 **Custom short URLs** and expiration options

---



