# 🚀 Bluestock IPO Data Platform (Django API)

## 📌 Overview

The **Bluestock IPO Data Platform** is a full-stack IPO management system built during my internship at **Bluestock Fintech (May 2025)**.

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

## 📡 API Documentation

Refer to:
https://github.com/bitz-1/bluestock-ipo-rest-api

---

## 🧑‍💻 Internship Experience

This project was developed as part of my internship at **Bluestock Fintech (May 2025 Batch L73)**, where I gained hands-on experience in:

* Building scalable backend APIs
* Working with real-world financial datasets
* Implementing secure authentication systems
* Deploying full-stack applications

---

## 📜 License

This project is licensed under Bluestock Fintech.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## 📬 Contact

For queries or collaboration:

* GitHub: https://github.com/Gayathri-Reddy874
