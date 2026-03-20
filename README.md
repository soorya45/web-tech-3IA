# web-tech-3IA


Here’s a clean, professional **README.md** you can directly use for your project 👇

---

# 📘 Student Management Web App (MongoDB Integrated)

## 📌 Overview

This project is a **Student Management Web Application** that allows storing and managing student details using **MongoDB** as the backend database. It is built using **HTML, CSS, JavaScript, and Node.js**.

The system provides a simple interface for adding, viewing, and managing student data efficiently.

---

## 🚀 Features

* 📝 Add student details
* 📂 Store data in MongoDB database
* 📊 View stored student records
* 🔄 Dynamic frontend interaction using JavaScript
* 🌐 Simple and responsive UI

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Node.js
* **Database:** MongoDB

---

## 📁 Project Structure

```
├── index.html        # Landing page
├── home.html         # Main dashboard
├── room.htm          # Room-related page
├── hist.html         # History page
├── succes.html       # Success page
├── common.htm        # Common layout

├── css/
│   ├── index.css
│   ├── home.css

├── js/
│   ├── index.js
│   ├── home.js
│   ├── room.js
│   ├── drive.js
│   ├── common.js
│   ├── app.js        # Main backend/server logic

├── assets/
│   ├── logo.png
│   ├── a.png
│   ├── b.png
│   ├── ad1.png
│   ├── backbtn.png

├── package.json
├── package-lock.json
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Setup MongoDB

* Install MongoDB locally OR use MongoDB Atlas
* Create a database (e.g., `studentDB`)
* Update your MongoDB connection string in `app.js`

Example:

```js
mongoose.connect("mongodb://localhost:27017/studentDB");
```

---

### 4️⃣ Run the server

```bash
node app.js
```

---

### 5️⃣ Open in browser

```
http://localhost:3000
```

---

## 📊 Functionality Flow

1. User enters student details via UI
2. Data is sent to backend (Node.js)
3. Backend stores data in MongoDB
4. Data can be retrieved and displayed

---

## 📷 Screens

### 🔐 Login Page
<img src="https://github.com/user-attachments/assets/7425de77-1d63-4c88-90ff-4598b8eedf9a" width="800"/>

---

### 📝 Student Form
<img src="https://github.com/user-attachments/assets/4114b621-e910-4024-a5af-43c588ae8f0a" width="800"/>

---

### 📊 Student Data Table
<img src="https://github.com/user-attachments/assets/67c484a3-120b-4344-a3d4-a5a9ec89903e" width="800"/>

---

### 🗄️ MongoDB Database
<img src="https://github.com/user-attachments/assets/b8139a62-6435-406a-b0d1-62394314cc7a" width="800"/>




---

## 🔐 Future Improvements

* User authentication (login/signup)
* Edit & delete student records
* Admin dashboard
* Search & filter functionality
* Deployment (Render / Vercel / AWS)

---

## 🤝 Contribution

Feel free to fork this repository and contribute improvements!

---

## 📧 Contact

**Soorya K**
📩 [ksoorya45@gmail.com](mailto:ksoorya45@gmail.com)

---

## ⭐ Acknowledgement

This project is created for learning and academic purposes to understand full-stack development with MongoDB.

---
