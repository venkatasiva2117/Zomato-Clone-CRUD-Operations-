# Zomato-Clone-CRUD-Operations-
Zomato Clone Backend — Spring Boot REST API for managing restaurants, menus, users, and orders with full CRUD operations using MySQL.

1. # 🍴 Zomato Clone - Backend (Spring Boot)

This project is a **Zomato Clone Backend** built using **Spring Boot**.  
It provides RESTful APIs to manage Restaurants, Menus, Users, and Orders with complete CRUD operations.

---

## 🚀 Features

- 🏨 Manage Restaurants (Add, Update, Delete, View)
- 🍔 Manage Menus linked with Restaurants
- 👥 Manage Users
- 🧾 Manage Orders between Users and Restaurants
- 💾 MySQL Database Integration
- ⚙️ Spring Data JPA for Repository Layer
- 🌐 RESTful API Endpoints

---

## 🧰 Tech Stack

- **Backend:** Spring Boot 3+, Spring Data JPA  
- **Database:** MySQL  
- **Language:** Java  
- **Build Tool:** Maven  
- **IDE:** Eclipse / IntelliJ IDEA  
- **Testing Tool:** Postman  

---


## 📁 Project Structure
src/
├── main/java/com/food/
│ ├── controller/ # REST Controllers
│ ├── entity/ # JPA Entities
│ ├── repository/ # JPA Repositories
│ └── service/ # Business Logic Layer
└── resources/
├── application.properties # DB configuration
└── static/templates

2.Open in IDE
Open the project in Eclipse or IntelliJ IDEA.

3.Configure Database
Update your MySQL credentials in application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/foodapp
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true


4.Run the Application
mvn spring-boot:run

5.Test Endpoints using Postman
--USER--
GET  /user
POST /user
PUT  /user/id
DELETE /user/id
---------------------------
--MENU--
GET  /menu
POST /menu
PUT  /menu/id
DELETE /menu/id
---------------------------
--RESTAURANT--
GET  /restaurant
POST /restaurant
PUT  /restaurant/id
DELETE /restaurant/id
---------------------------
--ORDERS--
GET  /orders
POST /orders
PUT  /orders/id
DELETE /orders/id

🧪 Sample JSON (Menu)

{
  "itemName": "Paneer Butter Masala",
  "description": "Rich creamy curry with paneer cubes",
  "price": 180.0,
  "rating": 4.5,
  "isAvailable": "Yes",
  "restaurantid": 1
}
--------------------------------------------------------------------------------------
🧑‍💻 Author
Venkata Siva
MCA Student | Full Stack Developer

--------------------------------------------------------------------------------------
🏁 Future Enhancements

Integrate Frontend (React or HTML/CSS/JS)
Implement Pagination and Filtering
Add JWT-based Authentication



