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
<img width="960" height="224" alt="{B29ADCD3-07D0-4F04-998E-667BFEDD58F9}" src="https://github.com/user-attachments/assets/3eb8ca85-5599-4d6a-a326-057e16995711" />
---
Example API Response:
---
<img width="721" height="232" alt="{3288CA47-B2FB-4CE1-AD3B-B2EB116341A5}" src="https://github.com/user-attachments/assets/3a7feeac-120e-467d-a2ad-5333f17dc7d6" />


```
[
{
"id":1,
"name":"Shivali",
"email":"shivali@gmail.com"
}
]
---
```

<img width="745" height="391" alt="{2A972E79-30BC-41D1-9231-40104C917E98}" src="https://github.com/user-attachments/assets/9d244f6d-a30b-4249-813b-c4f364ef88ce" />

---

<img width="960" height="503" alt="{E07BC39B-F6A6-4D54-8150-BE033F1A6FFD}" src="https://github.com/user-attachments/assets/069234ee-9359-4aeb-a8ce-b715a41f27f6" />

---

<img width="960" height="218" alt="{E3030E3E-986C-4402-A8FE-4B4A81AB05E9}" src="https://github.com/user-attachments/assets/6a59a914-f681-4d5a-a7a3-15816cb0a2b5" />

---

##GIT
<img width="505" height="351" alt="{3D0AD6CE-451B-4B2A-8172-C9BE9EE0DA28}" src="https://github.com/user-attachments/assets/ea3316d3-86d2-4d74-bd2d-7a32dfd28682" />

---

## 👩‍💻 Author

**Shivali**

GitHub:
https://github.com/Shivi714
