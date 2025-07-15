# ✅ To-Do List API

This is a **RESTful API** project developed with **Spring Boot** for managing a to-do list. It serves as an educational and practical example, providing a foundation for an explanatory article on building APIs with Java and Spring Boot.

📘 Read the full article about creating this API (portuguese): [How to Build a REST API with Spring Boot](https://www.linkedin.com/pulse/sua-primeira-api-rest-com-spring-boot-3-um-guia-passo-cau%C3%A3-sturaro-yaa2e/?trackingId=DPOkigKcqb0pqHBYtoKMFA%3D%3D)

---

## 🚀 Technologies Used

* **Java 17**
* **Spring Boot**
* **PostgreSQL** (database persistence)
* **Maven** (dependency management)
* **Postman** (API testing)
* **HTML + CSS + Vanilla JavaScript** (frontend)
* **Fetch API** (for consuming the API in the frontend)

---

## 📦 API Features

* ✅ Create a new task (`POST /tasks`)
* 📄 List all tasks (`GET /tasks`)
* 🔍 Get a task by ID (`GET /tasks/{id}`)
* ✏️ Update a task (`PUT /tasks/{id}`)
* 🗑️ Delete a task (`DELETE /tasks/{id}`)
* ☑️ Toggle task completion status (`PATCH /tasks/{id}`)

---

## 💎 Frontend Integration

The frontend was built with **pure HTML and CSS**, and consumes the API using **JavaScript with the Fetch API**, allowing:

* Adding tasks via form input
* Dynamically listing all tasks
* Marking tasks as completed
* Removing tasks from the list

