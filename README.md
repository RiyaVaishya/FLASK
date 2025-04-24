# 🧠 Flask Quiz App

A simple and elegant web-based quiz application built using **Flask**, **HTML**, **CSS**, and **Python**. Users can take a multiple-choice quiz, submit answers, and instantly see their score.

---

## 🚀 Features

- 🎯 3 predefined multiple-choice questions
- 🧮 Automatic score calculation
- 🖥️ Clean, user-friendly UI
- 🔁 Option to retake the quiz
- ⚙️ Flask + Jinja2 for dynamic rendering

---

> 💡 Replace the above with real screenshots after capturing them from your running app.

---

## 📁 Project Structure

quiz-app/
│
├── app.py                  # Main Flask app script
├── static/
│   └── style.css           # Stylesheet for the quiz UI
│
├── templates/
│   ├── quiz.html           # Template for the quiz page
│   └── result.html         # Template for the result page
│
└── README.md               # Project documentation

---

## 📘 Project Documentation

### 📌 Project Overview

**Flask Quiz App** is a lightweight web application that provides an interactive quiz experience.  
Built with Flask and Jinja2 templating, it demonstrates handling forms, processing user input, and rendering dynamic pages in Python.

---

### 🔧 How It Works

1. **Homepage (`/`)**  
   Displays quiz questions with multiple-choice options.  
   Users select answers and submit the form.

2. **Form Submission (`POST /`)**  
   The backend processes answers and calculates the score.

3. **Results Page**  
   Shows the user’s score and offers an option to retake the quiz.

---

### ⚙️ Key Concepts Used

- Flask routing (`@app.route`)  
- HTML form handling (`POST` requests)  
- Jinja2 templating for dynamic HTML  
- CSS styling for UI design  

---

### 🛣️ Future Roadmap

- Add more questions and categories  
- Integrate a database for question storage  
- Implement user authentication and score tracking  
- Deploy online using cloud hosting platforms  

---

## 🎯 Conclusion

This Flask Quiz App was a great learning experience to deepen my understanding of backend web development with Python.  
It helped me master routing, form handling, and dynamic content rendering using Flask and Jinja2.  

I’m excited to continue improving this project and build more full-stack web apps in the future!
