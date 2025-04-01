# 📚 E-Library Management System

## 🎥 Demo Video
https://drive.google.com/file/d/12wIrvABoK2qDNf9B1Qaj22F3kEln-LVP/view?usp=drive_link)

---

## 🚀 Introduction
The **E-Library Management System** is a MERN-STACK web application designed to manage books and users in a college library. The system includes role-based access control (Admin and User), book borrowing, due management, and automated notifications.

This project follows the **MVC architecture** for a modular and scalable design. 

---

## 🔥 Features Implemented

- ✅ **User Authentication** - Secure login & signup using JWT
- ✅ **Role-Based Authorization** - Admin and User access levels
- ✅ **OTP Verification** - Secure account verification via Email (NodeMailer)
- ✅ **Forgot & Reset Password** - Secure password recovery system
- ✅ **CRUD Operations** - Add, Edit, Delete, and Fetch Books with MongoDB
- ✅ **Book Issuing & Returning System** - Track borrowed books efficiently
- ✅ **Admin Panel** - Manage books & users with full control
- ✅ **Data Security** - Hash passwords, protect routes, and prevent unauthorized access
- ✅ **Automation** - Automatically remove overdue books
- ✅ **API Integration** - RESTful APIs with Express.js and MongoDB
- ✅ **Responsive UI** - Fully functional frontend with Tailwind CSS
- ✅ **State Management** - Clean and efficient state management with React-Redux and Redux Toolkit

---

## 📌 Tech Stack Used

### **Frontend:**
- React.js
- Tailwind CSS
- Redux Toolkit (for state management)

### **Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose ORM)
- JWT (JSON Web Token) for Authentication
- Bcrypt.js for Password Hashing
- NodeMailer (Email OTP Verification)
- NodeCron (Automation for overdue books)

---

## 📥 Installation Instructions

Follow these steps to set up the project on your local machine:

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/shreyaslal/IRIS_Web_Rec25_231CS156.git
cd IRIS_Web_Rec25_231CS156
```

### 2️⃣ **Backend Setup**
```bash
cd server
npm install
```
- Create a `.env` file with the following environment variables:
```env
PORT=4000
FRONTEND_URL=http://localhost:5173
MONGO_URI=your_mongodb_connection_string
SMTP_HOST = smtp.gmail.com
SMTP_SERVICE = gmail
SMTP_PORT = 465
SMTP_MAIL= your_email@gmail.com
SMTP_PASSWORD= 
JWT_SECRET_KEY=your_jwt_secret
JWT_EXPIRE=3d
COOKIE_EXPIRE=3
CLOUDINARY_CLIENT_NAME= 
CLOUDINARY_CLIENT_API=
CLOUDINARY_CLIENT_SECRET=

```
- Run the server:
```bash
npm run dev
```

### 3️⃣ **Frontend Setup**
```bash
cd client
npm install
npm run dev
```

---

## 🏃‍♂️ How to Run the Project

1. **Start the Backend**
   ```bash
   cd server
   npm run dev
   ```
2. **Start the Frontend**
   ```bash
   cd client
   npm run dev
   ```
3. Open `http://localhost:5173` in your browser.

---

## 🎯 User Roles & Permissions

| Role       | Permissions |
|------------|------------|
| **Admin**  | Manage books, users, dues, and overall system settings. |
| **User** | Browse books, borrow/return books. |

---

## ⚠️ Known Issues & Bugs

- Some UI components may not be fully optimized for mobile screens.
- Payment integration (bonus feature) is still under development.

---

## 📌 Future Enhancements

- **Payment Gateway**: Integrate Stripe/Noodlio Pay for due payments.
- **Mobile App**: Develop a mobile-friendly version using React Native.
- **Library Volunteers**: Allow students to volunteer as temporary librarians.
- **Dark Mode**: Implement a dark mode toggle for UI.

---

## 📚 References
- [MongoDB Documentation](https://www.mongodb.com/docs/)
- [React.js Documentation](https://reactjs.org/docs/getting-started.html)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [Node.js Documentation](https://nodejs.org/en/docs/)

---

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/3c93beea-0ee5-4452-b26e-3988fb04a3a0)


![image](https://github.com/user-attachments/assets/03ddb559-2ca6-4520-ab23-e7766f3923e3)

![image](https://github.com/user-attachments/assets/cad68999-b1d7-4429-bdc3-b59d209d55e5)

![image](https://github.com/user-attachments/assets/bebf28f5-ac83-4d5b-ad15-5e273dfa0c1f)

![image](https://github.com/user-attachments/assets/fd16bef5-3826-4848-ad56-1bde1af9c105)







---

