# StreakHero Backend 🚀

**StreakHero** is a gamified habit tracker where users can create habits, track completions, earn XP, and maintain streaks. This repository contains the **backend** built with **Node.js, Express, and MongoDB**.

---

## 📦 Tech Stack

- **Node.js** - JavaScript runtime
- **Express.js** - Web framework
- **MongoDB + Mongoose** - Database & ORM
- **JWT** - User authentication
- **Bcrypt** - Password hashing
- **Dotenv** - Environment variables
- **CORS** - Cross-origin requests

---

## ⚙️ Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/Rania-kh/streak-hero-backend.git
cd streak-hero-backend
```

2. **Install dependencies**

```bash
npm install
```

3. **Create a `.env` file** in the root:

```
MONGO_URI=your_mongodb_atlas_connection_string
JWT_SECRET=supersecretkey
PORT=5000
```

4. **Start the development server**

```bash
npm run dev
```

5. **Open your browser and go to:**

```
http://localhost:5000
```

You should see:

```
StreakHero backend is running 🚀
```

---

## 📂 Project Structure

```
streak-hero-backend/
│── src/
│   ├── controllers/   # Route handlers / logic
│   ├── middleware/    # Auth middleware
│   ├── models/        # Mongoose models (User, Habit, HabitLog)
│   ├── routes/        # Express routes
│   └── app.js         # Main entry point
│── .env               # Environment variables
│── .gitignore
│── package.json
│── README.md
```

---

## 🛠 Features (Planned)

- User registration and login with JWT
- Habit creation, editing, and deletion
- Habit completion logging
- XP system and level tracking
- Streak counter
- Secure routes with JWT authentication

---

## 🧹 Code Quality

- ESLint and Prettier configured for clean and consistent code.
- Run the following commands:

```bash
npm run lint   # Check for linting issues
npm run format # Auto-format code
```

---

## 📌 Notes

- Never commit your `.env` file — it contains sensitive information.
- This backend is designed to work with the **StreakHero frontend** built with Vue 3 + Pinia.
