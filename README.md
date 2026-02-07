# 🎓 Student & Enrollment Management System (APC-7923)

A **Spring Boot Microservices Project** that manages student information and course enrollments through a modular, service-oriented architecture.  
This project demonstrates **microservices communication, RESTful APIs, Feign clients, and database persistence** using **Spring Boot, JDBC, and Maven**, along with a **CLI-based frontend** for easy interaction.

---

## 🧩 Project Overview

The **Student & Enrollment Management System (SEMS)** streamlines academic operations such as **adding, updating, deleting, and viewing student data**, as well as **managing course enrollments**.  
It is built using **two independent Spring Boot microservices** — one handling **student management** and the other managing **enrollments** — both connected through an **API Gateway** that routes and integrates service communication seamlessly.  

Additionally, a **Command Line Interface (CLI)** client provides an interactive frontend to perform all operations directly from the terminal, with formatted table outputs for a professional experience.

---

## ⚙️ Microservices Architecture

| Service Name | Port | Description |
|---------------|------|-------------|
| **API Gateway** | `8080` | Routes requests to Student and Enrollment microservices |
| **Student Service** | `8081` | Handles all student-related operations (add, update, view, delete) |
| **Enrollment Service** | `8082` | Manages student course enrollments, updates, and deletions |
| **CLI Client** | - | Frontend command-line interface for user interaction |

---

## 👥 Team Members

| Name | Roll Number |
|------|--------------|
| **Nomita** | 2310990755 |
| **Nandini Jhunjhunwal** | 2310990747 |
| **Megha** | 2310990736 |
| **Mehak** | 2310990737 |

---

## 🧠 Features

✅ Microservices-based modular architecture  
✅ RESTful APIs for Student and Enrollment operations  
✅ API Gateway for unified routing and communication  
✅ CLI-based interactive frontend for user-friendly operations  
✅ Database persistence using Spring JDBC  
✅ Feign client for service-to-service communication  
✅ Clean and formatted table-style data display in CLI  
✅ Independent configuration and scalable design  

---

## 💻 CLI Functionalities

The CLI allows users to perform the following operations:

1. ➕ Add new student  
2. 📋 View all students  
3. 🔍 View specific student details  
4. ✏️ Update student details  
5. ❌ Delete student record  
6. 🏫 Enroll student in a course  
7. 📚 View all enrollments  
8. 🎯 View enrollments for a specific student  
9. 🔄 Update enrollment details  
10. 🗑️ Remove enrollment  
11. 🚪 Exit the system  

---
