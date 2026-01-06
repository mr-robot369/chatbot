
# 🤖 CUH Chatbot – Central University of Haryana

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)]
[![Django](https://img.shields.io/badge/Django-Web%20Framework-success.svg)]
[![Deployment](https://img.shields.io/badge/Deployment-Render-purple.svg)]

---

## 📌 Project Overview

**CUH Chatbot** is a web-based chatbot application developed to assist **new and existing students of the Central University of Haryana (CUH)**.
The chatbot provides quick answers related to **admissions, hostel facilities, academics, contact information, and general university queries**
through an interactive web interface.

The project is designed to resemble a **ChatGPT-like conversational experience**, while being **restricted and optimized for CUH-related queries only**.

---

## 🌐 Live Demo

🚀 **Live Website:**  
👉 https://chatbot-xrrq.onrender.com/

---

## 🧠 Key Features

- 💬 Interactive chatbot interface
- 📚 Predefined FAQs for common CUH queries
- 🏫 Admissions, hostel, and academic information
- 📨 Query submission form for unanswered questions
- 🖥️ Clean and responsive UI
- 🔒 Domain-restricted responses
- 🌐 Fully deployed backend

---

## 🧱 Tech Stack

| Layer | Technologies |
|-----|-------------|
| Backend | Python, Django |
| Frontend | HTML, CSS, JavaScript |
| Database | SQLite |
| Hosting | Render |
| Version Control | Git & GitHub |

---

## 📁 Project Structure

```text
chatbot/
├── chatapp/
├── chatbotproj/
├── templates/
├── static/
├── staticfiles/
├── manage.py
├── db.sqlite3
├── requirements.txt
└── README.md
```

---

## ⚙️ Local Setup

```bash
git clone https://github.com/mr-robot369/chatbot.git
cd chatbot
python -m venv venv
source venv/bin/activate   # Linux / macOS
venv\Scripts\activate    # Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Open: http://127.0.0.1:8000/

---

## 🔐 Django Admin Panel

```bash
python manage.py createsuperuser
```

Visit: http://127.0.0.1:8000/admin/

> Note: Django admin cannot be deployed on GitHub Pages.

---

## 🚀 Deployment

- Backend deployed on **Render**
- Static files collected for production
- Accessible publicly via web browser

---

## 🎓 Learning Outcomes

- Django backend development
- Static & media file handling
- Production deployment concepts
- Domain-specific chatbot design
- Backend vs static hosting limitations

---

## 📜 License

Open-source project for educational purposes.

---

## ⭐ Resume Description

> Built and deployed a Django-based chatbot for Central University of Haryana, featuring an interactive UI, domain-specific responses, and production deployment on Render.

---

## 🔗 Links

- GitHub Repo: https://github.com/mr-robot369/chatbot
- Live Site: https://chatbot-xrrq.onrender.com/
