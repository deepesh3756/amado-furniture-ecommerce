🪑 Amado Furniture – E-Commerce Website










A full-stack Spring Boot e-commerce application developed as a major college project.
It simulates a real-world online furniture store, providing product browsing, cart actions, checkout, authentication, and role-based admin management.

🚀 Features
🛍 User Features

Browse all furniture items

View product details

Add to cart / remove from cart

Update cart quantities

Checkout flow

User login/signup

Persistent session-based cart

🛠 Admin Features

Add/update/delete products

Manage categories

Role-based secure admin login

Dashboard for viewing users & orders

⚙ Technical Features

Spring Boot MVC layered architecture

Thymeleaf dynamic server-side views

Spring Security authentication + roles

JPA/Hibernate ORM

H2 & MySQL supported

Clean controller–service–repository design

🧱 Architecture Overview
Presentation Layer (Thymeleaf, Controllers)
        ↓
Service Layer (Business Logic)
        ↓
Repository Layer (JPA Repositories)
        ↓
Database (H2/MySQL)

📁 Project Structure
amado-furniture-ecommerce/
 ├── src/main/java/com/amado/
 │     ├── controller/
 │     ├── model/
 │     ├── repository/
 │     ├── service/
 │     ├── security/
 │     └── AmadoApplication.java
 ├── src/main/resources/
 │     ├── templates/
 │     ├── static/
 │     └── application.properties
 ├── pom.xml
 ├── .gitignore
 └── README.md

🛠 Tech Stack
Backend

Java

Spring Boot

Spring MVC

Spring Security

Spring Data JPA (Hibernate)

Maven

Frontend

HTML, CSS, JavaScript

Thymeleaf templates

Bootstrap

Database

H2 (file-based dev DB)

MySQL (production-ready option)

▶️ Run the Project Locally
1️⃣ Clone the repository
git clone https://github.com/deepesh3756/amado-furniture-ecommerce.git
cd amado-furniture-ecommerce

2️⃣ Build the project
mvn clean install

3️⃣ Run the application
mvn spring-boot:run

4️⃣ Open the website
http://localhost:8080/

🔑 Default Credentials
Admin Login
Email: admin@gmail.com
Password: admin

User

Create a new user via signup page.

🖼 Screenshots (Add After Uploading Images)
![Homepage]()
![Product List]()
![Cart Page]()
![Admin Dashboard]()

🧪 API Endpoints (Short Overview)

(Useful for interviews)

Method	Endpoint	Description
GET	/	Homepage
GET	/shop	Browse products
GET	/product/{id}	View product details
POST	/cart/add/{id}	Add to cart
GET	/cart	View cart
POST	/checkout	Checkout
GET	/admin/**	Admin dashboard
📝 License

This project is licensed under the MIT License.

🤝 Contributing

Pull requests are welcome.
