- **Website** : https://mohitmore.pythonanywhere.com/core/
- **App (PWA)** : 
[![Download APK](https://img.shields.io/badge/Download-Android%20APK-brightgreen?logo=android)](https://github.com/Shubham-393/testassistance/raw/main/AI%20Test.apk)

---
# 📚 Test Assistance

**Test Assistance** is a Django-based application designed to streamline the process of creating and managing tests and assessments. It offers a user-friendly interface for educators to design tests and for students to take them efficiently.

---

## 🌟 Features

✅ **User Authentication**: Secure login and registration system.

✅ **Test Creation**: Educators can create and customize tests with various question types.

✅ **Real-time Grading**: Automatic grading system providing immediate feedback.

✅ **Analytics Dashboard**: Visual representation of test results and performance metrics.  

---

## 🛠️ Tech Stack

### 📌 Frontend:
- **HTML5**
- **CSS3 (Bootstrap 5)** 
- **JavaScript**

### 📌 Backend:
- **Python**  
- **Django**  

### 📌 Database:
- **SQLite** (default), can be configured to use **PostgreSQL** or MySQL 

### 📌 Authentication:
- **Google OAuth**  

### 📌 AI Integration:
- **Google Generative AI**  

---

## 🚀 Installation Guide

Follow these steps to **set up project locally**:

### 1️⃣ Clone the Repository

`git clone https://github.com/Shubham-393/testassistance.git`
`cd testassistance `

### 2️⃣ Create and Activate Virtual Environment

`python3 -m venv .venv`
`source .venv/bin/activate  # On Windows: .venv\Scripts\activate`

### 3️⃣ Install Dependencies

`pip install -r requirements.txt`

### 4️⃣ Apply Migrations

`python manage.py migrate`

### 5️⃣ Run the Development Server

`python manage.py runserver`
Your project is now running at:
🔗 http://127.0.0.1:8000/core/

---

## 📊 Project Structure
```
testassistance/
│── core/               # Main app
│   ├── models.py       # Database models
│   ├── views.py        # Business logic
│   ├── urls.py         # URL routes
│   ├── templates/      # HTML templates
│   ├── static/         # Static files (CSS, JS)
│   ├── forms.py        # Django forms
│   ├── utils.py        # Helper functions
│── rentalhub/          # Django project settings
│   ├── settings.py     # Project configuration
│   ├── urls.py         # Main URL routing
│── requirements.txt    # Dependencies
│── manage.py           # Django management script
│── README.md           # Project documentation
```

---

## 🤝 Contributing

Contributions are welcome! Follow these steps to contribute:

Fork the Repository.  

Create a New Branch:  
`git checkout -b feature-branch-name  `

Commit Your Changes:  
`git commit -m 'Add new feature' ` 

Push to GitHub:  
`git push origin feature-branch-name  `

Create a Pull Request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 📞 Contact

If you have any questions, feel free to reach out:
📧 **Email**: khotshubham393@gmail.com  
🔗 **GitHub**: [Shubham-393](https://github.com/Shubham-393)
