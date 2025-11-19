Title: Amado Furniture – E-Commerce Website
Amado Furniture is a full-stack Spring Boot e-commerce website built as a major college project.
It provides a complete furniture shopping experience with product listings, cart management, authentication, and an admin dashboard for managing products and categories.

🚀 Features
🛍 User Features
Browse furniture products
View product details
Add items to cart
Update cart quantities
Checkout page
User signup & login
Session-based cart management

🛠 Admin Features
Add/Edit/Delete products
Manage categories
View/manage orders
Role-based login (ADMIN & USER)

⚙ Backend Features
Spring Boot MVC
Service/Repository layered architecture
Spring Security authentication
JPA/Hibernate ORM
H2 / MySQL support
Thymeleaf template engine

🗂 Project Structure
amado-furniture/
 ├── src/
 │   └── main/
 │        ├── java/com/amado/
 │        │      ├── controller
 │        │      ├── model
 │        │      ├── repository
 │        │      ├── service
 │        │      ├── security
 │        │      └── AmadoApplication.java
 │        └── resources/
 │             ├── templates/     (Thymeleaf Views)
 │             ├── static/        (CSS, JS, Images)
 │             └── application.properties
 ├── pom.xml
 ├── mvnw / mvnw.cmd
 └── README.md
