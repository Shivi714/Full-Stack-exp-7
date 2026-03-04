# Spring Boot Student CRUD API

## 📌 Project Description

This project is a simple **Spring Boot REST API** that performs basic **CRUD operations** for managing student data using **Spring Boot, Spring Data JPA, and MySQL**.

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
* Postman

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

Example Request JSON

```
{
"name": "Shivali",
"email": "shivali@gmail.com"
}
```

---

## ▶️ Running the Project

1. Clone the repository

```
git clone https://github.com/Shivi714/Full-Stack-exp-7.git
```

2. Open the project in **Eclipse IDE**

3. Run the application

```
Exp7Application.java
```

4. Open browser or Postman

```
http://localhost:8080/api/students
```

---

# 📷 Output Screenshots

## API Output in Browser

<img width="960" height="224" src="https://github.com/user-attachments/assets/3eb8ca85-5599-4d6a-a326-057e16995711" />

---

## Example API Response

<img width="721" height="232" src="https://github.com/user-attachments/assets/3a7feeac-120e-467d-a2ad-5333f17dc7d6" />

Example JSON Response

```
[
 {
  "id": 1,
  "name": "Shivali",
  "email": "shivali@gmail.com"
 }
]
```

---

## Empty Database Response

<img width="745" height="391" src="https://github.com/user-attachments/assets/9d244f6d-a30b-4249-813b-c4f364ef88ce" />

---

## Postman Testing

<img width="960" height="503" src="https://github.com/user-attachments/assets/069234ee-9359-4aeb-a8ce-b715a41f27f6" />

---

## Spring Boot Server Running

<img width="960" height="218" src="https://github.com/user-attachments/assets/6a59a914-f681-4d5a-a7a3-15816cb0a2b5" />

---

## Git Repository Push

<img width="505" height="351" src="https://github.com/user-attachments/assets/ea3316d3-86d2-4d74-bd2d-7a32dfd28682" />

---

## 👩‍💻 Author

**Shivali**

GitHub Profile
https://github.com/Shivi714
