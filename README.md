# 🎓 Online Course Assessment System

A Django-based web application that extends the existing **Online Course** platform by adding a comprehensive **Assessment Feature**. Students can enroll in courses, take assessments, and view their scores, while instructors can create and manage assessments.

---

## 📌 Project Information

| Item                | Details                                                     |
| ------------------- | ----------------------------------------------------------- |
| **Repository Name** | `tfjzl-final-cloud-app-with-database`                                   |
| **Project Name**    | Online Course Assessment System                             |
| **Framework**       | Django                                                      |
| **Language**        | Python                                                      |
| **Database**        | SQLite3 (Default), PostgreSQL, or MySQL                     |
| **Deployment**      | IBM Cloud Foundry (Default) or any supported cloud platform |

---

## 📖 Project Overview

The project builds upon an existing **Online Course** application by integrating an **Assessment Module**. This enhancement enables instructors to create quizzes and assessments, while students can complete them and receive scores based on their answers.

---

## ✨ Features

* 👤 User Registration and Authentication
* 📚 Course Enrollment
* 📝 Assessment and Quiz Management
* ✅ Multiple Choice Questions
* 📊 Automatic Score Calculation
* 📈 Assessment Results
* 🗄️ Database-backed Storage
* ☁️ Cloud Deployment Support

---

## 🛠️ Development Environment

You may develop this project using either of the following:

### IBM Skills Network Theia

* Use the provided Online Course project as the starting point.
* Recreate the project structure in your Theia workspace.
* Save your workspace before closing the browser.

### Local Development

Set up your own development environment using:

* Python 3.x
* Django
* pip
* Virtual Environment (recommended)
* Any supported IDE (VS Code, PyCharm, etc.)

---

## 💾 Supported Databases

The application supports any database compatible with Django:

* SQLite3 (Default)
* PostgreSQL
* MySQL

---

## ☁️ Deployment

The default deployment platform is **IBM Cloud Foundry**, but the application can also be deployed to other cloud providers that support Django applications.

---

## 📂 Project Structure

```text
onlinecourse/
├── onlinecourse/
├── courses/
├── templates/
├── static/
├── db.sqlite3
├── manage.py
└── README.md
```

---

## 🗂️ Assessment Module

The new Assessment Feature includes:

* Assessment model
* Question model
* Choice model
* Student submissions
* Score calculation
* Result display

The database schema follows the provided **Entity Relationship (ER) Diagram**.

---

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/<your-username>/onlinecourse-assessment.git
```

Navigate into the project:

```bash
cd onlinecourse-assessment
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Apply migrations:

```bash
python manage.py migrate
```

Start the development server:

```bash
python manage.py runserver
```

Open your browser and visit:

```
http://127.0.0.1:8000/
```

---

## 📚 Technologies Used

* Python
* Django
* HTML5
* CSS3
* Bootstrap
* SQLite3

---

## 📄 License

This project was developed for educational purposes as part of the IBM Skills Network Django Final Project.

---

## 👨‍💻 Author

**Evangel Yoshiya G. Aranas**
