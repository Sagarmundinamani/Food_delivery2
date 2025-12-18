🍽️ Food Delivery Application

A full-stack Food Delivery Web Application built using Java, JDBC, Servlets, JSP, MySQL, and HTML/CSS.
The system allows users to browse restaurants, view menus, place orders, and manage order history, while admins can manage restaurants and menu items.

📌 Features
👤 User Module

User Registration & Login

Browse Restaurants

View Menus

Place Food Orders

View Order History

Secure session management

🏪 Restaurant (Admin) Module

Admin Login

Add / Update / Delete Restaurants

Manage Menu Items

Activate / Deactivate Restaurant

View Orders for a Restaurant

🛒 Order Management

Add items to cart

Place orders

Order status tracking

Order items mapping

Total amount calculation

🧱 Tech Stack
💻 Backend

Java (JDK 8+)

JDBC

Servlets & JSP

Apache Tomcat

🎨 Frontend

HTML5

CSS3

JavaScript

🗄️ Database

MySQL

DB Design using dbdiagram.io

🗃️ Database Schema
Tables Used

user

restaurant

menu

orders

orderitems

Relationships

User → Restaurant (Admin)

Restaurant → Menu

User → Orders

Orders → OrderItems

Menu → OrderItems


⚙️ Installation & Setup

1️⃣ Clone the Repository
git clone https://github.com/Sagarmundinamani/Food_Delivery.git

2️⃣ Database Setup

Create a MySQL database

Run the SQL schema provided in the project

Update DB credentials in DBConnection.java

3️⃣ Server Configuration

Install Apache Tomcat (9+ recommended)

Add Tomcat server in Eclipse

4️⃣ Run the Project

Start the Tomcat server

Open browser and navigate to:

http://localhost:8080/Food_Delivery/

🔐 Security Measures

Prepared Statements (Prevents SQL Injection)

Session-based Authentication

Role-based Access Control

🚀 Future Enhancements

Online Payment Integration

JWT Authentication

REST API using Spring Boot

React Frontend

Order Notifications

Rating & Reviews System

📚 Learning Outcomes

Hands-on experience with Java Web Development

DAO Design Pattern

Database Relationships & Normalization

MVC Architecture

Real-time project exposure

👨‍💻 Author

Sagar Mundinamani
Computer Science | Full Stack Developer
📧 Email:mundinamanisagar@gmail.com

🔗 GitHub: https://github.com/Sagarmundinamani

⭐ Acknowledgements

Tap Academy
