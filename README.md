# 🏡 AirBnB Clone – Backend

## 📖 Overview

This project replicates the core backend functionality of the AirBnB platform. It includes user management, property listings, bookings, payments, and reviews — built for scalability and real-world learning.

---

## 🚀 Objectives

- Handle user registration & authentication
- Manage property listings
- Enable bookings & payments
- Support reviews & ratings
- Ensure performance with indexing & caching

---

## 🛠️ Core Features

- **RESTful APIs** via Django REST Framework
- **GraphQL Support** for flexible data querying
- **User Authentication** and CRUD operations
- **Property & Booking Management**
- **Payment Integration**
- **Review System**
- **Performance Optimization** with Redis & indexing

---

## ⚙️ Technology Stack

| Technology       | Purpose                                                                 |
|------------------|-------------------------------------------------------------------------|
| **Python**       | The main programming language used to build backend logic.              |
| **Django**       | A high-level Python web framework used for rapid backend development.   |
| **Django REST Framework** | Extension of Django for building RESTful APIs.                |
| **PostgreSQL**   | A powerful relational database system for storing structured data.      |
| **GraphQL**      | A query language for flexible and efficient API requests and responses. |
| **Celery**       | Handles background tasks such as email notifications and scheduling.    |
| **Redis**        | An in-memory data store used for caching and message brokering.         |
| **Docker**       | Containerizes the application for consistent deployment across systems. |
| **CI/CD Pipelines** | Automates testing, integration, and deployment processes.            |

---

## 📌 Key Endpoints (REST)

- `/users/` → `GET`, `POST`  
- `/users/{id}/` → `GET`, `PUT`, `DELETE`  
- `/properties/` → `GET`, `POST`  
- `/bookings/` → `GET`, `POST`  
- `/payments/` → `POST`  
- `/reviews/` → `GET`, `POST`  

---

## 👥 Team Roles

- **Backend Devs** – API logic & integration  
- **DB Admin** – Schema, indexing, optimization  
- **DevOps** – Deployment, scaling, CI/CD  
- **QA** – Testing & bug fixing  

---

## 📬 Contact

For collaboration or questions, open an issue or submit a pull request.
