📦 Courier Management System

A web-based application designed to streamline the process of booking, tracking, and managing courier services. This system improves operational efficiency by automating parcel processing, branch management, employee management, and real-time tracking.

📘 Abstract

The Courier Management System digitalizes the operations of courier companies by replacing manual work with an efficient, automated platform. It provides shipment tracking, courier entry, branch management, and report generation. This increases accuracy, reduces delays, and enhances customer satisfaction.

⭐ Key Features
🔐 Authentication

Secure Admin Login

Session-based access

📦 Courier Management

Add new courier entries

Update shipment status

Date-wise & delivered-wise listing

Parcel tracking using unique tracking ID

🏢 Branch & Staff Management

Add new branches/offices

Add and manage officers/managers

Office-wise courier display

📊 Reports & Search

Search courier using tracking ID

Generate reports

Edit courier details

🖥 User Interface

Clean PHP-based UI

Simple navigation

Interactive dashboard

🛠 Technologies Used
Layer	Technology
Frontend	HTML, CSS, JavaScript
Backend	PHP
Database	MySQL
Server	XAMPP / WAMP
IDE	VS Code
🏗 System Architecture
🔹 1. Context Diagram

The system interacts with:

Admin → manages couriers, branches, officers

Customer → tracks shipment

Database → stores courier, staff, office data

🔹 2. DFD (Level-0 & Level-1)

Core modules:

Login Module

Courier Module

Branch Module

Tracking Module

🧩 Modules Overview
1️⃣ Admin Module

Login

Add/Edit/Delete couriers

Add offices

Add officers

View courier lists

Generate reports

2️⃣ Courier Tracking Module

User enters tracking ID → system displays:

Sender/Receiver details

Current status

Delivery updates

3️⃣ Office Management Module

Add new office

Assign officers

Office-wise courier monitoring

4️⃣ Reports Module

Date-wise list

Delivered parcel list

Courier search

🗄 Database Structure
Key tables:

courier

offices

officers

tracking

delivery_status

SQL File:

courier/database/courier_db.sql

▶️ How to Run the Project
1️⃣ Install XAMPP / WAMP

Enable:

Apache

MySQL

2️⃣ Copy Project Files

Place the project folder into:

C:\xampp\htdocs\

3️⃣ Import Database

Open phpMyAdmin

Create database:

courier_db


Import SQL:

courier/database/courier_db.sql

4️⃣ Update DB Configuration

File:

courier/database.php

5️⃣ Run the Project

Open browser:

http://localhost/courier

📸 Screenshots (Add after uploading images)

Login Page

Dashboard

Add Courier

Courier List

Tracking Page

Reports Page

📍 Project Output

This system provides:

Complete digital courier booking

Real-time shipment tracking

Admin panel

Office & staff management

Faster and error-free courier processing

📚 Conclusion

The Courier Management System digitalizes courier operations, reduces errors, and increases processing speed. It offers easy tracking, fast courier management, and a simple UI—ideal for small to medium courier companies.
