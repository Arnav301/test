# 🔗 URL Shortener

A simple and efficient URL Shortener backend built using Node.js, Express, and MongoDB.
This project allows users to shorten long URLs and redirect them using a short, unique link.

# 🚀 Features

- 🔒 Shorten long URLs into easy-to-share short links

- 🔁 Redirect to original URLs instantly

- 💾 MongoDB integration for storing and retrieving links

- ⚙️ Environment configuration with dotenv

- 🧩 Automatic server reload using nodemon

| Category  | Technologies Used   |
| --------- | ------------------- |
| Backend   | Node.js, Express.js |
| Database  | MongoDB             |
| Utilities | dotenv, nodemon     |


# ⚙️ Installation

## 💡 Frontend/Deployment integration instructions coming soon!

1️⃣ Clone the repository
git clone https://github.com/<your-username>/url-shortener.git
cd url-shortener

2️⃣ Install dependencies
npm install

3️⃣ Configure environment variables

Create a .env file in the root directory and add:

PORT=5000
MONGO_URI=your_mongodb_connection_string
BASE_URL=http://localhost:5000

4️⃣ Run the server
npm run dev


The server runs using nodemon on your defined PORT.


# 📡 API Endpoints
Method	Endpoint	Description
POST	/api/shorten	Shortens a long URL
GET	/:shortId	Redirects to the original URL

# 🧠 Future Enhancements

- 🔐 Add user authentication

- 📊 Click tracking & analytics dashboard

- 🌐 Frontend using React.js

- ☁️ Deploy to Render / Vercel
