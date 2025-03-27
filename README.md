# GF Web Application

## 🚀 Project Overview

GF Web Application is a full-stack web platform designed to digitalize employee attendance tracking, automate payroll calculations, and manage financial accounting for income and expenses. The system also provides cost calculation functionalities to streamline business operations. Built with React on the frontend and Express.js on the backend, this project provides a seamless user experience with robust API functionality.

## 🌐 Demo Screenshots

Here are some screenshots showcasing the key features of the application:

### Login Page
![Login Page](https://github.com/jerry19980310/Project-Demo/blob/main/GF_SYSTEM/screenshots/LoginPage.jpg)

### **Clock In and Out**
![Attendance Page](https://github.com/jerry19980310/Project-Demo/blob/main/GF_SYSTEM/screenshots/AttendancePage.png)

### **Payroll Calculation**
![Salary Page](https://github.com/Project-Demo/blob/main/GF_SYSTEM/screenshots/SalaryPage.png)

### **Expense Management**
![Expend Page1](https://github.com/jerry19980310/Project-Demo/blob/main/GF_SYSTEM/screenshots/ExpendPage1.jpg)
![Expend Page2](https://github.com/jerry19980310/Project-Demo/blob/main/GF_SYSTEM/screenshots/ExpendPage2.jpg)
![Expend Page3](https://github.com/jerry19980310/Project-Demo/blob/main/GF_SYSTEM/screenshots/ExpendPage3.jpg)

### **Employee Management**
![Approval Box Page](https://github.com/jerry19980310/Project-Demo/blob/main/GF_SYSTEM/screenshots/ApprovalBoxPage.png)
![Attendance Query Page](https://github.com/jerry19980310/Project-Demo/blob/main/GF_SYSTEM/screenshots/AttendanceQueryPage.png)

### **Web Push Notification **
![Web Push](https://github.com/jerry19980310/Project-Demo/blob/main/GF_SYSTEM/screenshots/WebPush.jpg)


## 🛠️ Tech Stack

- **Frontend:** React, MUI
- **Backend:** Node.js, Express.js
- **Database:** MySQL
- **Deployment:** Synology NAS Docker + Reverse Proxy (linked to backend host)

## ✨ Features

- ✅ **User Authentication** - Secure login/logout system
- ✅ **Digital Attendance Tracking** - Employees can clock in/out electronically
- ✅ **Automated Payroll Calculation** - Computes salary based on attendance and bonuses
- ✅ **Financial Accounting** - Tracks company income and expenses
- ✅ **Cost Calculation** - Generates cost reports for business analysis
- ✅ **Web Push Notification** - Push notification to managers

## 📂 Project Structure

```
GF_Project/
│── frontend/    # React application
│── backend/     # Express API
│── screenshots/ # Project demo screenshots
│── README.md    # Project documentation
```

## 🛠️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/jerry19980310/GF_Frontend.git
git clone https://github.com/jerry19980310/GF_Backend.git
```

### 2️⃣ Install dependencies

**Frontend:**

```bash
cd GF_Frontend
npm install
npm start
```

**Backend:**

```bash
cd GF_Backend
npm install
node index.js
```

### 3️⃣ Environment Variables

Create a `.env` file in the backend directory and specify required keys:

```
PORT=3000
DB_HOST=your_database_host
DB_USER=your_database_user
DB_PASSWORD=your_database_password
DB_NAME=your_database_name
JWT_SECRET=your_secret_key
```

## 📝 Author

Developed by **Yu-Chia-Sheng KAO**

---
