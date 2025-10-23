# 🍽️ Online Canteen System

The **Online Canteen System** is a web-based application designed to simplify food ordering and management within a canteen. It allows students, staff, and administrators to efficiently manage menus, place orders, and track transactions digitally.

---

## 🚀 Features

- 🧑‍💻 **User Accounts** — Registration and login for students and canteen staff.  
- 🍔 **Menu Management** — Add, update, and delete food items with prices.  
- 🛒 **Order Placement** — Users can browse available meals and place orders online.  
- 💳 **Payment Tracking** — Records and manages transactions for each order.  
- 📊 **Admin Dashboard** — Manage users, orders, and inventory.  

---

## 🧩 Project Structure

<img width="348" height="249" alt="image" src="https://github.com/user-attachments/assets/ddc754aa-83d6-418e-9bdb-38d69b7f8b5b" />


---

## ⚙️ Installation

### Prerequisites
- **Java JDK 11+**
- **Apache Maven**
- **MySQL Server**
- **Web Browser**

### Steps
1. **Clone or extract** the project:
   git clone https://github.com/yourusername/online-canteen-system.git
   
2. Import database:
  Open MySQL and run canteendb.sql or create_tables.sql.

3. Configure database connection in
  src/main/resources/application.properties (if applicable).

4. Build and run the project:
  mvn spring-boot:run

5. Access the app in your browser:
   http://localhost:8080

## 🧠 Technologies Used

Java (Spring Boot)

MySQL

HTML / CSS / JavaScript

Maven

RESTful APIs

### 📚 Database Setup

Use the provided SQL files to create and populate the database:
  source canteendb.sql;

Make sure your MySQL database name matches the configuration in your project (default: canteendb).
