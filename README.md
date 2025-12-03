🏥 Hospital Management System

A lightweight and efficient Java Swing + MySQL desktop application that digitalizes hospital operations such as patient management, doctor records, admissions, billing, staff handling, and more.

✨ Features

👨‍⚕️ Doctor Management – Add, update, delete, search

🧑‍🤝‍🧑 Patient Management – Register, update, delete

🧪 Laboratory Services – Add lab tests & charges

🛏 Room & Ward Management – Availability & charges

🏥 Patient Admission – Assign rooms & doctors

📄 Discharge Module – Add discharge summary

💰 Billing System – Auto calculation based on stay + services

👨‍🔧 Staff Records – Manage nurses & ward staff

🏗️ Tech Stack

☕ Java (Swing) – GUI & business logic

🗄 MySQL – Database

🔌 JDBC – Java–MySQL connection

🛠 NetBeans – Development IDE

🧩 Architecture

Two-Tier Client–Server Architecture

🖥 Client: Java Swing app (UI + logic)

🗃 Server: MySQL database

🔗 Direct CRUD operations using JDBC

Fast, simple, and perfect for desktop-based hospital workflows.

🚀 How to Run

Install JDK, MySQL, and NetBeans

Create a database and import the provided SQL file

Update your DB credentials in DatabaseConnection.java:

String url = "jdbc:mysql://localhost:3306/hospitaldb";
String user = "root";
String pass = "";


Run the project from your IDE 🎉

📁 Project Structure
/src
/sql
/diagrams
README.md

📸 Screenshots

(Add your screenshots here)

👥 Contributors

Falak Irfan

Kubra Zareen

Arusa Nadeem

📌 Note

This project was developed as part of a Software Design & Architecture course. You are free to customize and enhance it.
