# Todo List Application

## 📌 Project Overview

This **Todo List Application** is a simple yet structured backend-driven project built to manage daily tasks efficiently. The project focuses on **clean backend logic, RESTful API design, and database interaction**, rather than flashy UI.

This project is intentionally kept simple to demonstrate **core Java + Spring Boot fundamentals**, which are critical for backend developer roles.

---

## 🛠️ Tech Stack

* **Backend:** Java, Spring Boot
* **Database:** MySQL
* **ORM:** Spring Data JPA / Hibernate
* **Build Tool:** Maven
* **API Style:** RESTful APIs
* **IDE:** IntelliJ IDEA
* **Tools:** Postman, Git, GitHub

---

## ✨ Features

* Create new tasks
* Update existing tasks
* Mark tasks as completed
* Delete tasks
* View all tasks
* Basic status handling (Pending / Completed)

---

## 🧱 Project Structure

```
src/main/java
 └── com.example.todo
     ├── controller
     ├── service
     ├── repository
     └── model

src/main/resources
 └── application.properties
```

---

## ⚙️ Configuration

Update the **application.properties** file:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/todo_db
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect
```

---

## ▶️ How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/todo-list-application.git
   ```

2. Open the project in **IntelliJ IDEA**

3. Create the database:

   ```sql
   CREATE DATABASE todo_db;
   ```

4. Update database credentials in `application.properties`

5. Run the application as a **Spring Boot Application**

6. Test APIs using **Postman**

---

## 📬 API Endpoints (Sample)

* `GET /todos` – Fetch all tasks
* `POST /todos` – Create a new task
* `PUT /todos/{id}` – Update a task
* `DELETE /todos/{id}` – Delete a task

---

## 🎯 Purpose of This Project

This project was built to:

* Strengthen **Spring Boot CRUD operations**
* Practice **REST API design**
* Understand **JPA & database mapping**
* Build confidence for **backend interviews**

---

## 🚀 Future Enhancements

* User authentication (JWT)
* Task priority levels
* Due dates and reminders
* Pagination and sorting
* Frontend integration

---

## 👨‍💻 Author

**Sauraj Singh**
Java Backend Developer (Spring Boot)

---

## ⭐ Note

This project focuses on **backend correctness and structure**, not UI complexity. It is meant for learning and interview preparation.

⭐ If you find this project useful, give it a star!
