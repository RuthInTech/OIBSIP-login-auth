# 🔐 Simple Login Authentication System

## 📌 Project Overview

This project is a simple Login Authentication System built using HTML, CSS, and JavaScript. It allows users to register, log in, access a secured dashboard page, and log out.

The system uses browser localStorage to simulate authentication and session handling.

This project was developed as part of an internship assignment with Oasis Infobyte.

---

##  Features

- User Registration
- User Login
- Basic Form Validation
- Secured Dashboard Page
- Logout Functionality
- Session Control using localStorage
- Page Redirection
- Clean UI with CSS Styling

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Browser localStorage

---

## 📂 Project Structure

project-folder/
│
├── index.html (Login Page)
├── register.html (Registration Page)
├── dashboard.html (Secured Page)
├── style.css (Styling File)
└── README.md


---

## 🔑 How It Works

1. The user registers by entering a username and password.
2. The user data is stored in the browser using localStorage.
3. During login:
   - The entered credentials are compared with the stored data.
4. If the credentials match:
   - The user is redirected to the dashboard.
   - Login status is saved in localStorage.
5. The dashboard checks login status before granting access.
6. Logout clears the session and redirects back to the login page.

---

##  Disclaimer

This is a frontend-only demo project and is NOT secure for production use.  
Passwords are stored in localStorage for educational purposes only.

In real-world applications:
- Passwords should be encrypted/hashed.
- Authentication should be handled on the backend.
- A secure database should be used.

---

##  Learning Outcomes

- Understanding authentication flow
- Handling user input validation
- Working with localStorage
- Implementing conditional page redirection
- Debugging JavaScript errors
- Managing multi-page web applications

---

##  Acknowledgment

This project was completed as part of the Oasis Infobyte Internship Program.
