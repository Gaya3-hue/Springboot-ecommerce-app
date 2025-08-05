# 🛒 Shopping Cart Spring Boot App

A production-ready multi-vendor **eCommerce backend** built using **Java Spring Boot**, featuring authentication, product & user management, cart, orders, and secure REST APIs.

---

## Features

- User Registration & JWT Login
- Product CRUD (Create, Read, Update, Delete)
- Add/Remove Items to Cart
- Place Orders
- Email Notifications using Java Mail Sender
- Admin Panel – Approve products, manage users

---

## Tech Stack

- **Backend:** Spring Boot, Spring Security, JWT
- **Database:** MySQL
- **Mail:** Java Mail Sender
- **Build Tool:** Maven
- **Cloud-Ready:** Easily deployable to AWS/GCP/Azure

---

## Project Structure
shopping-cart-spring-boot-main/
│
├── src/
├── .mvn/
├── .gitignore
├── pom.xml
├── mvnw / mvnw.cmd
└── README.md


---

## 🧪 How to Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/Gaya3-hue/Springboot-ecommerce-app.git
cd Springboot-ecommerce-app

# 2. Configure DB in src/main/resources/application.properties

# 3. Run using Maven
./mvnw spring-boot:run


