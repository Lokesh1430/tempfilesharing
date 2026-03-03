# 🚀 Temporary File Sharing Web Application

![Node.js](https://img.shields.io/badge/Node.js-18.x-green)
![Express.js](https://img.shields.io/badge/Express.js-Backend-lightgrey)
![Deployment](https://img.shields.io/badge/Deployment-Render-blue)
![Status](https://img.shields.io/badge/Project-Active-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

A lightweight and secure **temporary file sharing platform** that allows users to upload and share files **without login credentials**. Files are automatically deleted after **30 minutes**, ensuring privacy, security, and optimized storage management.

---

## 🌐 Live Demo
https://tempfilesharing.onrender.com/

## 📂 GitHub Repository
https://github.com/Lokesh1430/tempfilesharing

---

## 📌 Project Objective

The objective of this project is to provide a fast and secure way to share files between users without requiring authentication. The system ensures temporary access with automatic expiration and deletion after 30 minutes to maintain security and server efficiency.

---

## ✨ Key Features

- 📤 Upload files without login/signup  
- 🔗 Generate temporary shareable URLs  
- ⏳ 30-minute automatic file expiration  
- 🗑️ Auto deletion after expiry  
- ❌ Cancel upload functionality  
- 📋 Display available files with access links  
- ⚡ Fast and minimal user interface  
- 🌐 Live cloud deployment on Render  

---

## 🛠️ Tech Stack

### Backend
- Node.js
- Express.js
- Multer (File Upload Middleware)

### Frontend
- HTML5
- CSS3
- JavaScript

### Deployment
- Render (Cloud Hosting Platform)

---

## ⚙️ How It Works

1. User uploads a file through the web interface.
2. The server stores the file temporarily.
3. A unique URL is generated for sharing.
4. The file remains accessible for 30 minutes.
5. After 30 minutes:
   - The file is automatically deleted.
   - The URL becomes invalid.

This ensures secure, temporary, and optimized file sharing.

---

## 🔐 Security & Expiration Logic

- No login required for quick sharing  
- Files stored temporarily on the server  
- Automatic cleanup mechanism removes expired files  
- Prevents storage overload  
- Reduces long-term unauthorized access risks  

---

## 📂 Project Structure

tempfilesharing/  
│── server.js  
│── package.json  
│── public/  
│   ├── index.html  
│   ├── style.css  
│   └── script.js  
│── uploads/  

---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository

git clone https://github.com/Lokesh1430/tempfilesharing.git  
cd tempfilesharing  

### 2️⃣ Install Dependencies

npm install  

### 3️⃣ Run the Application

node server.js  

Open in browser:  
http://localhost:3000  

---

## 📊 Advantages

✔ No authentication required  
✔ Automatic expiration improves security  
✔ Prevents server storage overload  
✔ Lightweight and fast system  
✔ Demonstrates backend file handling and scheduling logic  
✔ Real-world deployment experience  

---

## ⚠️ Limitations

- Not designed for large-scale enterprise usage  
- No user-based file ownership tracking  
- File size depends on server configuration  
- No encryption (if not implemented)  

---



## 📜 License

This project is licensed under the MIT License.
