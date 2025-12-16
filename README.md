# 🏥 Hospital Management System (HMS)

A **full-stack Hospital Management System** built using **Spring Boot Microservices** and **React (TypeScript)**, designed to manage patients, doctors, appointments, prescriptions, inventory, and analytics dashboards efficiently.

---

## 🚀 Features

### 👨‍⚕️ Patient Module
- Patient profile management  
- View appointment history  
- Monthly visit analytics  
- Disease distribution insights  
- Medication history tracking  

### 🩺 Doctor Module
- Doctor profile & specialization details  
- Today’s appointments view  
- Patient visit analytics  
- Disease-based insights  

### 🛠 Admin Module
- System-wide dashboard  
- Patient & doctor management  
- Appointment monitoring  
- Inventory & medicine stock overview  

---

## 📊 Dashboard & Analytics
- 📈 Monthly appointment counts (Patient / Doctor / Admin)
- 🧠 Disease distribution (Donut Charts)
- ⏰ Today’s appointments
- 📦 Medicine sales & stock validation
- 📊 Interactive charts (Area & Donut charts)

---

## 🏗️ System Architecture

```text
Frontend (React + TypeScript)
        ↓
Backend (Spring Boot Microservices)
        ↓
Appointment MS | Prescription MS | Inventory MS
        ↓
Database (Relational DB)
