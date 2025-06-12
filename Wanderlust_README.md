# 🏕️ Wanderlust - Full-Stack Travel Listing App

**Wanderlust** is a full-featured travel listing web application inspired by Airbnb. It allows users to browse, create, edit, and review travel destinations. Built using Node.js, Express.js, MongoDB, and EJS templating, it includes robust authentication, session management, and clean UI design.

---

## 🔧 Features

- ✍️ CRUD operations for travel listings
- 🧾 User reviews with ratings
- 🔐 Authentication with Passport.js
- 💾 Session storage using MongoDB Atlas
- 🌐 Flash messaging for success/error alerts
- 📦 Clean project architecture and modular routes
- 🛡️ Environment configuration using `.env` and `dotenv`

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Atlas)
- **Templating:** EJS with Ejs-Mate layout engine
- **Authentication:** Passport.js with LocalStrategy
- **Session Management:** Express-session, connect-mongo
- **Validation & Errors:** Custom middleware using ExpressError
- **Flash Messages:** connect-flash

---

## 🧪 Installation & Setup

### 1️⃣ Clone the repository:
```bash
git clone https://github.com/aditmishra2609/wanderlust.git
cd wanderlust
```

### 2️⃣ Install dependencies:
```bash
npm install
```

### 3️⃣ Create `.env` file:
```env
ATLASDB_URL=your_mongodb_connection_string
SECRET=your_session_secret
```

### 4️⃣ Start the development server:
```bash
node app.js
```

Visit `http://localhost:8080/listings` in your browser.

---

## 📂 Project Structure

```
wanderlust/
├── routes/
│   ├── listing.js
│   ├── review.js
│   └── user.js
├── models/
│   └── user.js
├── utils/
│   └── ExpressError.js
├── views/
│   ├── listings/
│   ├── partials/
│   └── error.ejs
├── public/
│   └── (static files like CSS/JS/images)
├── app.js
├── package.json
└── .env


**Adit Kumar Mishra**  
GitHub: [@aditmishra2609](https://github.com/aditmishra2609)

---

> This project was developed as part of a backend/full-stack learning journey.
