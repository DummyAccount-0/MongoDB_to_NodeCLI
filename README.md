# 📘 Student Management CLI App (Node.js + MongoDB)

A simple Command-Line Interface (CLI) application for managing student records using **Node.js**, **MongoDB**, and **Mongoose**.

---

## 🔧 Features

- ➕ Insert a new student  
- 📋 View all students  
- ✏️ Update an existing student's details  
- 🗑️ Delete a student by ID  
- ❌ Exit the app safely  

---

## 🗂️ Tech Stack

- Node.js  
- MongoDB (local instance)  
- Mongoose ODM  
- Readline module for CLI interface  

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/Ravi098987/MongoDB_Node_CLI.git
cd MongoDB_Node_CLI
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start MongoDB

Make sure MongoDB is running locally on your system.

#### For Linux/macOS:

```bash
sudo service mongod start
```

#### For Windows (via MongoDB Compass or terminal):

```bash
net start MongoDB
```

> ✅ **Default MongoDB URI used**: `mongodb://localhost:27017/toPushGitdb`

---

## 🚀 Run the Application

```bash
node app.js
```

You'll see a CLI menu like this:

```
📘 Student Management Menu
1. ➕ Insert Student
2. 📋 View All Students
3. ✏️ Update Student
4. 🗑️ Delete Student
5. ❌ Exit
```

---

## 📂 Project Structure

```
MongoDB_Node_CLI/
├── app.js             # Main CLI application
├── models/
│   └── User.js        # Mongoose schema for student
├── package.json       # NPM configuration
├── package-lock.json
```
