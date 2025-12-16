# 🏥 Hospital Management System (HMS)

A **full-stack Hospital Management System** built using **Spring Boot Microservices** and **React (TypeScript)**.  
The system manages **patients, doctors, appointments, prescriptions, medicines, inventory, and dashboards** with secure APIs and modern UI.

---

## 📌 Project Overview

The Hospital Management System (HMS) is designed to digitalize hospital operations and provide **role-based dashboards** for:

- 👤 Patients  
- 🩺 Doctors  
- 🛠 Admins  

The system uses **microservices architecture**, **DTO-based APIs**, and **interactive dashboards** to ensure scalability, performance, and clean separation of concerns.

---

## ✨ Key Features

### 👨‍⚕️ Patient Features
- View profile details
- Monthly visit analytics
- Disease distribution charts
- Medication history
- Profile picture upload

### 🩺 Doctor Features
- Manage daily appointments
- View patient disease statistics
- Monthly appointment analytics
- Profile management with specialization

### 🛠 Admin Features
- System-wide dashboards
- Manage patients and doctors
- Monitor appointments
- Medicine stock & sales tracking

---

## 📊 Dashboards & Analytics

- Monthly appointment count (Patient / Doctor / Admin)
- Disease distribution using donut charts
- Today’s appointments view
- Medication history overview
- Inventory and medicine sales analysis

---

## 🧑‍💻 Tech Stack

### Backend
- Java 17
- Spring Boot
- Spring Data JPA
- JPQL (DTO projections)
- Microservices Architecture
- Lombok
- JWT / Bearer Token Authentication

### Frontend
- React
- TypeScript (.tsx)
- React Hooks (useState, useEffect)
- Chart Library (Area & Donut Charts)
- CSS Flexbox & Grid Layout

### Database
- MySQL
- Optimized Aggregation Queries

---

## 🔐 Security

- JWT-based authentication
- Bearer token authorization
- Role-based access control (Patient / Doctor / Admin)
- Protected media endpoints for profile images
- Secure API testing using Postman

---

## ⚙️ Core Functional Highlights

- Prescription import with medicine details
- Frequency-based dosage calculation
- Automatic quantity calculation using duration
- Stock validation to prevent overselling
- Batch-wise inventory tracking
- DTO-based backend responses for performance
- Clean architecture: Controller → Service → Repository

---

## 🧪 API Testing

- APIs tested using **Postman**
- Authorization handled via **Bearer Token**
- Separate endpoints for:
  - Patient Dashboard APIs
  - Doctor Dashboard APIs
  - Admin Dashboard APIs
- Graceful handling of empty data (returns empty lists instead of errors)

---

## 🎨 UI Highlights

- Card-based layout for patients and doctors
- Responsive dashboards with interactive charts
- Avatar initials displayed when profile image is missing
- Hover effects, shadows, and smooth UI transitions
- Clean, beginner-friendly, and readable UI design

---

## 🏗 Project Structure

```text
hospital-management-system
│
├── backend
│   ├── appointment-service
│   ├── prescription-service
│   ├── inventory-service
│   ├── media-service
│
├── frontend
│   ├── dashboard
│   ├── patient
│   ├── doctor
│   ├── admin
│
└── README.md

```
## 🚀 Future Enhancements

- Redis caching for improved dashboard performance  
- Kafka integration for event-driven communication  
- Real-time, dynamic dashboards  
- Advanced admin role and permission management  
- Dark / Light theme support  
- Performance optimization for large-scale datasets  

## 👤 Author

**Ganesh Sonune**  
🎓 B.Tech – Computer Engineering  
💻 Java Backend & Full-Stack Developer  
📊 Data Analytics Enthusiast  

