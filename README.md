# 📝 Quora Posts – CRUD Web App

A simple Quora-style Post Management application built using **Node.js**, **Express**, and **MongoDB**.  
Users can create, read, update, and delete posts, while the UI displays all posts in a clean layout with author name and description.

---

## 🎯 Features

- ➕ Create New Posts
- 👀 View Individual Post Details
- ✏️ Edit Existing Posts
- ❌ Delete Posts
- 🎨 Clean and Responsive UI
- 🗄️ MongoDB Database Integration

---

## 🛠️ Tech Stack

| Layer | Technology |
|------|------------|
| Backend | Node.js, Express.js |
| Database | MongoDB + Mongoose ODM |
| Views/Templates | EJS / HTML / CSS |
| Tools | Postman, npm, VS Code |

---

## ⚙️ Installation & Setup

Make sure **Node.js** and **MongoDB** are installed on your system.

```bash
# Clone the project
git clone https://github.com/yourusername/quora-posts-app.git

# Navigate into directory
cd quora-posts-app

# Install dependencies
npm install

# Setup Database URL (optional)
# In .env file:
MONGO_URL=your_mongodb_connection_string

# Run server
npm start
