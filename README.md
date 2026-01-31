# Enterprise & People Management System (Spring Boot API) 🚀

A modern, scalable RESTful API built with **Spring Boot 3.4** to manage physical and legal entities within a corporate environment. This project implements the **MVC (Model-View-Controller)** architectural pattern and demonstrates high-level proficiency in Java-based back-end development.



### 🛠 Tech Stack & Tools

* **Backend Framework:** Spring Boot 3.4.0 (Spring Web, Data JPA, DevTools).
* **Language:** Java 17.
* **Database:** H2 (In-memory for testing) & Support for MySQL/PostgreSQL.
* **Project Management:** Maven for dependency handling and build automation.
* **Productivity:** Lombok for clean, boilerplate-free code.

### 🚀 Key Features

* **Full RESTful Lifecycle:** Implementation of all CRUD operations with standardized HTTP methods (GET, POST, PUT, DELETE).
* **Persistence Layer:** Automated database schema management using Spring Data JPA and Hibernate.
* **Environment Flexibility:** Pre-configured for H2 development with easy migration to production databases like MySQL/Postgres.
* **Standardized API Endpoints:** Clean and predictable URL structures for managing people and companies.

### 📡 API Documentation (Endpoints)

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `GET` | `/api/pessoas` | List all registered entities |
| `POST` | `/api/pessoas` | Create a new entity (Physical/Legal) |
| `GET` | `/api/pessoas/{id}` | Retrieve detailed data by ID |
| `PUT` | `/api/pessoas/{id}` | Update existing records |
| `DELETE` | `/api/pessoas/{id}` | Remove an entity from the system |

### 🔧 Setup & Installation

1. **Clone & Build:**
   ```bash
   git clone [https://github.com/GabrielVFC/enterprise-management-system.git](https://github.com/GabrielVFC/enterprise-management-system.git)
   mvn clean install
