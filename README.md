# 📝 User Posts Platform

![MongoDB](https://img.shields.io/badge/MongoDB-green?logo=mongodb&logoColor=white)
![Express](https://img.shields.io/badge/Express-black?logo=express&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-lightgreen?logo=node.js&logoColor=white)
![EJS](https://img.shields.io/badge/EJS-red?logo=ejs&logoColor=white)
![Open Source](https://img.shields.io/badge/Open%20Source-💻-brightgreen)
![Made with ❤️ by Aniket](https://img.shields.io/badge/Made%20with-❤️-red)

> 👤 A simple web platform where users can **signup/login** and create **personal posts (self-context posts)**. Built using **MongoDB, Express, Node.js, and EJS**.

---

## 🚀 **Overview**

This project is a **full-stack user post application** with these features:  

- 📝 User authentication (signup/login)  
- 🖊️ Users can create posts with title and content  
- 📄 Users can view their own posts  
- ⚡ Simple and responsive UI using EJS templating  

This project is perfect for learning **CRUD operations, authentication, session management, and dynamic rendering** with Node.js and MongoDB.

---

## 🧰 **Tech Stack**

| Tech | Description |
|------|-------------|
| 🗄️ MongoDB | Stores users and posts |
| ⚙️ Express.js | Backend server and API routes |
| 🟢 Node.js | Server runtime environment |
| 🖥️ EJS | Dynamic HTML rendering for frontend |
| 💻 bcrypt & express-session | Secure password storage and session management |

---

## ⚙️ **Features**

- ✅ Signup and login system  
- ✅ Password hashing with bcrypt  
- ✅ Session-based authentication  
- ✅ Create, read, and view personal posts  
- ✅ Dynamic rendering using EJS  

---

## ⚙️ **How It Works**

1. **User Authentication**  
   - Users sign up with email/password  
   - Passwords hashed with bcrypt  
   - Session created on login for persistent authentication  

2. **Create Posts**  
   - After login, users can create a post with title and content  
   - Posts are stored in MongoDB linked to the user ID  

3. **View Posts**  
   - Users can view a list of their own posts dynamically rendered with EJS  

---

## 💻 **Setup & Usage**

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/user-posts-platform.git
cd user-posts-platform
