![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
# 🏥 Hospital Management System (HMS) using Flask

## 📌 Project Overview
Hospitals require efficient systems to manage **patients, doctors, appointments, and treatments**.  
Many healthcare facilities still rely on manual registers or disconnected software systems, leading to scheduling conflicts, poor record management, and difficulty in tracking patient history.

This **Hospital Management System (HMS)** is a web-based application designed to streamline hospital operations by providing **role-based access** for Admins, Doctors, and Patients using a centralized database.

---

## 🎯 Objectives
- Digitize hospital record management
- Enable role-based access for Admin, Doctor, and Patient
- Prevent appointment conflicts
- Maintain complete patient treatment history
- Ensure secure and efficient interaction between all stakeholders

---

## 🧑‍⚕️ User Roles & Functionalities

### 🔑 Admin (Hospital Staff)
- Pre-existing superuser (created programmatically)
- Add, update, or remove doctor profiles
- View and manage all appointments
- Search doctors and patients by name or specialization
- Edit or blacklist doctors and patients
- View dashboard statistics:
  - Total doctors
  - Total patients
  - Total appointments

---

### 👨‍⚕️ Doctor
- Login to view assigned appointments
- View patient details and treatment history
- Mark appointments as **Completed** or **Cancelled**
- Provide diagnosis, prescriptions, and treatment notes
- Set availability for the next 7 days

---

### 🧑‍💼 Patient
- Register, login, and manage profile
- Search doctors by specialization and availability
- Book, reschedule, or cancel appointments
- View upcoming and past appointments
- Access diagnosis, prescriptions, and treatment records

---

## 🧾 Key Entities

### Appointment
- Appointment ID
- Patient ID
- Doctor ID
- Date & Time
- Status (Booked / Completed / Cancelled)

### Treatment
- Appointment ID
- Diagnosis
- Prescription
- Doctor Notes

### Department / Specialization
- Department ID
- Department Name
- Description
- Registered Doctors

*(Additional fields and tables are added as needed.)*

---

## ⚙️ Core Features
- Prevent multiple appointments for the same doctor at the same time
- Dynamic appointment status updates
- Search functionality for doctors, patients, and specializations
- Complete patient treatment history tracking
- Secure authentication and role-based authorization
- Programmatic database creation (no manual DB setup)

---

## 🛠️ Technology Stack

### Backend
- **Flask**
- **SQLite**
- **Flask-SQLAlchemy**
- **Flask-Login**

### Frontend
- **HTML**
- **CSS**
- **Bootstrap**
- **Jinja2 Templates**

---

## 📂 Project Structure
- ├── app.py / main.py # Application entry point
- ├── models.py # Database models
- ├── routes/ # Application routes
- ├── templates/ # HTML templates
- ├── static/ # CSS & assets
- ├── requirements.txt # Dependencies
- ├── README.md # Documentation

## Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate     # Windows: venv\Scripts\activate

## Install dependencies:
pip install -r requirements.txt

##  Run the application:
python app.py

## Access the app at:
http://127.0.0.1:5000/

---

## 📊 Evaluation Readiness

- Database created programmatically

- Role-based authentication implemented

- Live demo supported on local machine

- Modular and extensible design

- Ready for viva and feature modification

---

## 🚀 Future Enhancements

- REST APIs for appointments and users

- Charts for admin analytics

- Email notifications for appointments

- Enhanced validation and security

- Improved UI/UX design

---

## 👤 Author

Nagavengadeshwaran S
📧 Email: 24f1000802@ds.study.iitm.ac.in

🔗 GitHub: https://github.com/Nv1023