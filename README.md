# Individual_Project_1
# 🎓 SchoolsDB – School Management Database System

## 📘 Overview
The **SchoolsDB** project is a relational database system designed to manage and organize key information within a school environment. It handles data about **departments, teachers, students, courses, classrooms, schedules, and enrollments**, providing a structured way to store and connect relationships among them.

This project was developed for **CIS 344 – Database Design** under **Prof. Yanilda Peralta Ramos** at CUNY during **Fall 2025** by **Rokia Touray**.

---

## 🧠 Project Objectives
- Design a database schema for a school system using **MySQL Workbench**.
- Model entities and their relationships using both **Chen** and **UML ER diagrams**.
- Implement and forward-engineer the database into **MySQL** using SQL scripts.
- Demonstrate understanding of **database normalization, foreign keys, and constraints**.

---

## 🧩 Entities and Relationships

| Entity | Description |
|--------|--------------|
| **Departments** | Contains department names and office locations. |
| **Teachers** | Stores teacher information and their assigned department. |
| **Students** | Contains student personal and academic data. |
| **Courses** | Holds course information linked to departments. |
| **Classroom** | Represents classrooms with room numbers and capacities. |
| **Schedule** | Manages class scheduling, linking courses, teachers, and classrooms. |
| **Enrollment** | Tracks which students are enrolled in which scheduled classes. |

---

## 🔗 Relationships Summary
- One **Department** can have many **Teachers** and **Courses**.
- One **Teacher** can teach multiple **Schedules**.
- One **Course** can have many **Schedules**.
- One **Schedule** can have many **Enrollments**.
- One **Student** can be enrolled in many **Schedules** (through Enrollment).
- One **Classroom** can host many **Schedules**.

---

## 🧱 Database Implementation
The database was built using **MySQL Workbench** and forward-engineered into SQL.

### Files Included:
- `SchoolsDB.mwb` – MySQL Workbench model (UML ER Diagram)
- `SchoolsDB.sql` – SQL script for database and table creation
- `Chen_ER_Diagram.jpg` – Hand-drawn Chen ER Diagram
- `UML_ER_Diagram.png` – UML ER Diagram exported from MySQL Workbench
- `report.pdf` – Final project report

