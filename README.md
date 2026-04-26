# 🚀 Bluestock IPO Data Platform (Django API)

🚀 Backend API for IPO Data Management built using Django REST Framework

---

## 📌 Overview

The **Bluestock IPO Data Platform** is a full-stack IPO management platform developed during my internship at **Bluestock Fintech (May 2025)**.

This platform enables efficient management of IPO listings with complete CRUD functionality and provides a scalable backend API for financial data operations.

---

## 🎯 Features

* 📊 IPO Listing Management (Create, Read, Update, Delete)
* 🔐 Admin Authentication & Authorization
* 🗄️ PostgreSQL Database Integration
* 📩 Email Configuration Support
* ⚡ RESTful API Architecture
* 🧩 Modular Django Applications
* 🌐 Full-stack separation (Backend + Client)

---

## 🏗️ Project Structure

```
Bluestock_Project/
│
├── backend/        # Django REST API
│   └── API/
│
├── client/         # Frontend / Client Application
│   └── frontend/
│
└── README.md
```

---

## ⚙️ Tech Stack

* **Backend:** Django, Django REST Framework
* **Database:** PostgreSQL (Neon DB)
* **Frontend:** Django Client / Web Interface
* **Tools:** Git, GitHub

---

## 📦 Requirements

* Python 3.x
* pip
* PostgreSQL
* Virtualenv (recommended)

---

## 📥 Clone the Repository

```bash
git clone https://github.com/Gayathri-Reddy874/Bluestock_ipo-data-platform-django-api.git
cd Bluestock_ipo-data-platform-django-api
```

---

## 🧪 Installation & Setup

### 🔹 Step 1: Create Virtual Environments

```bash
# Backend
cd Bluestock_Project/backend
python -m venv backenv

# Client
cd ../client
python -m venv frontenv
```

---

### 🔹 Step 2: Activate Environments

```bash
# Backend
source backenv/bin/activate   # Linux/Mac
backenv\Scripts\activate      # Windows

# Client
source frontenv/bin/activate
frontenv\Scripts\activate
```

---

### 🔹 Step 3: Install Dependencies

```bash
# Backend
cd ../backend/API
pip install -r requirements.txt

# Client
cd ../../client/frontend
pip install -r requirements.txt
```

---

### 🔹 Step 4: Configure Environment Variables

Create a `.env` file inside the backend directory:

```env
EMAIL_USER=your_email
EMAIL_PASS=your_password
EMAIL_FROM=your_email

PGHOST=your_host
PGDATABASE=your_database
PGUSER=your_user
PGPASSWORD=your_password
```

---

### 🔹 Step 5: Apply Migrations

```bash
python manage.py migrate
```

---

### 🔹 Step 6: Create Superuser

```bash
python manage.py createsuperuser
```

---

### 🔹 Step 7: Run Backend Server

```bash
python manage.py runserver 8001
```

👉 Access Admin Panel:
http://127.0.0.1:8001/admin

---

### 🔹 Step 8: Run Client Server

```bash
python manage.py runserver 8000
```

---

## 📡 Sample API Endpoints

| Method | Endpoint        | Description          |
| ------ | --------------- | -------------------- |
| GET    | /api/ipos/      | Get all IPO listings |
| POST   | /api/ipos/      | Create new IPO       |
| GET    | /api/ipos/{id}/ | Get IPO details      |
| PUT    | /api/ipos/{id}/ | Update IPO           |
| DELETE | /api/ipos/{id}/ | Delete IPO           |

---

## 📡 API Documentation

Refer to:
https://github.com/bitz-1/bluestock-ipo-rest-api

---

## 🧑‍💻 Internship Experience & Contribution

This project was developed as part of my internship at **Bluestock Fintech (May 2025 Batch L73)**, where I contributed to the development of an IPO management platform.

### 🔹 My Contributions

* Developed and tested **RESTful APIs** using Django and Django REST Framework
* Implemented **CRUD operations** for IPO data management
* Worked on **database integration** using PostgreSQL
* Assisted in backend logic development and API structuring
* Participated in debugging, testing, and improving application performance

### 🔹 Key Learnings

* Gained hands-on experience in real-world backend development workflows
* Improved understanding of API design and data handling
* Learned to work in a team-based development environment
* Understood best practices in code structure, version control, and deployment

---

## ⚠️ Note

This repository contains a simplified and adapted version of the original internship project.
Sensitive or proprietary components have been excluded.

---

## 📜 License

This project is for educational and portfolio purposes only.
Developed as part of an internship at Bluestock Fintech.
Some parts of the original project may be proprietary to the organization.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## 📬 Contact

For queries or collaboration:

* GitHub: https://github.com/Gayathri-Reddy874
