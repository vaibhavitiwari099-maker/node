# node

# 🚀 Node.js REST API

A simple REST API built using Node.js and Express to perform CRUD operations (Create, Read, Update, Delete).

---

## 📌 Features

- Get all users
- Add a new user
- Update user data
- Delete a user

---

## 🛠️ Tech Stack

- Node.js
- Express.js

---

## 📂 Project Structure

```
node-app/
│── node_modules/
│── server.js
│── package.json
│── README.md
```

---

## ⚙️ Installation

1. Clone the repository:
```
git clone https://github.com/vaibhavitiwari099-maker/node.git
```

2. Go to project folder:
```
cd node
```

3. Install dependencies:
```
npm install
```

---

## ▶️ Run the Project

Start the server:
```
node server.js
```

Server will run on:
```
http://localhost:3000
```

---

## 📡 API Endpoints

### 🔹 GET Users
```
GET /users
```

### 🔹 POST User
```
POST /users
```
Body (JSON):
```
{
  "name": "Vaibhavi",
  "age": 19
}
```

### 🔹 PUT User
```
PUT /users/:id
```

### 🔹 DELETE User
```
DELETE /users/:id
```

---

## 🧪 Testing

Use Postman to test API endpoints.

---

## 🔧 GitHub Commands

Initial setup:
```
git init
git add .
git commit -m "Initial commit"
```

Push to GitHub:
```
git remote add origin https://github.com/your-username/node-rest-api.git
git branch -M main
git push -u origin main
```

Update later:
```
git add .
git commit -m "Update"
git push
```

---

## 📜 License

This project is licensed under MIT License.

---

## 👩‍💻 Author

Vaibhavi Tiwari  
GitHub: https://github.com/vaibhavitiwari099-maker

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
