# Clinic Patient Record & Prescription System

A web-based Clinic Patient Record and Prescription Management System developed using Django. The system is designed to simplify clinic operations by managing patient information, maintaining medical records, and generating prescriptions through a centralized platform.

## 🚀 Features

- **Patient Management** – Register, update, view, and manage patient information
- **Doctor Management** – Maintain doctor profiles and related information.
- **Patient Records** – Store and access patient medical history and records.
- **Prescription Management** – Create, manage, and view patient prescriptions.
- **Authentication System** – Secure login, registration, and logout functionality.
- **User Management** – Manage user accounts and access.
- **Database Management** – Store and organize clinic-related information.
- **Admin Dashboard** – Manage application data through Django Admin.

## 🛠️ Technologies Used

- **Backend:** Python, Django
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite
- **Authentication:** Django Authentication System
- **Version Control:** Git & GitHub

## 📂 Project Structure

```text
Clinic-Patient-Record-Prescription-System/
│
├── clinic/
├── patients/
├── prescriptions/
├── templates/
├── static/
├── media/
├── db.sqlite3
├── manage.py
├── requirements.txt
└── README.md
```

*Note: The project structure may vary depending on the implementation.*

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Arafat-shuvo/Clinic-Patient-Record-Prescription-System.git
```

### 2. Navigate to the Project Directory

```bash
cd Clinic-Patient-Record-Prescription-System
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

**Windows:**

```bash
venv\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Apply Database Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 7. Create a Superuser

```bash
python manage.py createsuperuser
```

### 8. Run the Development Server

```bash
python manage.py runserver
```

Open your browser and visit:

```text
http://127.0.0.1:8000/
```

## 🎯 Project Objectives

- Digitize patient information and medical records.
- Simplify prescription creation and management.
- Reduce manual paperwork in clinic operations.
- Improve accessibility and organization of patient data.
- Provide a structured platform for clinic management.

## 👨‍💻 Developer

Jahannur Akter 
Parijat Ashraf 
Kazi Shamin Tasawar 
Md. Arafat Hossain 

- GitHub: [@Arafat-shuvo](https://github.com/Arafat-shuvo)

---

⭐ If you find this project useful, consider giving it a star!
