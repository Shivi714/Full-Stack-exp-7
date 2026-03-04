# Spring Boot Student CRUD API

## 📌 Project Description

This project is a simple **Spring Boot REST API** that performs **CRUD operations (Create, Read)** for Student data using **Spring Boot, Spring Data JPA, and MySQL**.

The API allows users to:

* Add a new student
* View all students
* View a student by ID

---

## 🛠 Technologies Used

* Java
* Spring Boot
* Spring Data JPA
* MySQL
* Maven
* Eclipse IDE
* REST API

---

## 📁 Project Structure

```
exp-7
│
├── controller
│   └── StudentController.java
│
├── model
│   └── Student.java
│
├── repository
│   └── StudentRepository.java
│
├── service
│   └── StudentService.java
│
├── Exp7Application.java
└── application.properties
```

---

## ⚙️ Database Configuration

```
spring.datasource.url=jdbc:mysql://localhost:3306/spring_hibernate_db
spring.datasource.username=root
spring.datasource.password=University@12
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
server.port=8080
```

---

## 🔗 API Endpoints

### 1️⃣ Get All Students

```
GET /api/students
```

### 2️⃣ Get Student by ID

```
GET /api/students/{id}
```

### 3️⃣ Add Student

```
POST /api/students
```

Example JSON:

```
{
"name":"Shivali",
"email":"shivali@gmail.com"
}
```

---

## ▶️ Running the Project

1. Clone the repository

```
git clone https://github.com/Shivi714/Full-Stack-exp-7.git
```

2. Open the project in Eclipse

3. Run

```
Exp7Application.java
```

4. Open browser

```
http://localhost:8080/api/students
```

---

## 📷 Output

Example API Response:

```
[
{
"id":1,
"name":"Shivali",
"email":"shivali@gmail.com"
}
]
```

(Add screenshot here)

---

## 👩‍💻 Author

**Shivali**

GitHub:
https://github.com/Shivi714
