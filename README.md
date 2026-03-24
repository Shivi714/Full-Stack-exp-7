<img width="570" height="425" alt="{41C4400B-D565-4D32-8D3A-96836CD548A5}" src="https://github.com/user-attachments/assets/41665f7b-f2e4-4a95-8b31-cf1cf04e2873" /># Spring Boot Student CRUD API

## 📌 Project Description

This project is a **Spring Boot REST API** that performs basic **CRUD operations** for managing student data using **Spring Boot, Spring Data JPA, and MySQL**.

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
exp-8
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
<img width="569" height="450" alt="{2E1BF817-02DF-446F-BFC0-7C326F5E4E16}" src="https://github.com/user-attachments/assets/dfedbcc3-b781-4ba3-8997-b64023c9ada1" />


```

### 2️⃣ POST (Add Student)

```
GET /api/students/{id}
<img width="571" height="432" alt="{DCE4625B-61D6-4BFD-AF39-3C510124C575}" src="https://github.com/user-attachments/assets/2e28db31-e1ae-416f-90c0-e9d4295c798d" />


```

### 3️⃣ Add Student

```
POST /api/students
<img width="900" height="403" alt="{BFCB82B7-A445-4947-8E41-AB3C3A8A3326}" src="https://github.com/user-attachments/assets/cc3ec1b1-03af-4bb9-bf30-e95bfff1f42d" />

```

Example Request JSON

```
{
"name": "Shivali",
"email": "shivali@gmail.com"
}
```
### 3️⃣ GET by ID
<img width="570" height="425" alt="{41C4400B-D565-4D32-8D3A-96836CD548A5}" src="https://github.com/user-attachments/assets/5fa18ec4-df8b-409c-b6e8-3a780ba0bfb1" />

---
### PUT (Update Student)
<img width="565" height="429" alt="{B365C28A-E291-454B-9F39-956146ABB578}" src="https://github.com/user-attachments/assets/7999c4d6-d181-4923-82e1-650c238e61ea" />

---
### DELETE Student

<img width="572" height="422" alt="{1A3B8309-3F24-4BC3-83E0-550698551A2B}" src="https://github.com/user-attachments/assets/166c2798-5d37-47f9-b1ee-413c1994fa76" />

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

## 🌐 API Output in Browser

<img width="960" height="218" src="https://github.com/user-attachments/assets/6a59a914-f681-4d5a-a7a3-15816cb0a2b5" />

---

## 📄 Example API Response



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

## 🗂 Empty Database Response

<img width="960" height="224" src="https://github.com/user-attachments/assets/3eb8ca85-5599-4d6a-a326-057e16995711" />

---

## 📬 Postman Testing

<img width="721" height="232" src="https://github.com/user-attachments/assets/3a7feeac-120e-467d-a2ad-5333f17dc7d6" />

---

## 💻 Eclipse IDE

<img width="960" height="503" src="https://github.com/user-attachments/assets/069234ee-9359-4aeb-a8ce-b715a41f27f6" />

---

## 🚀 Spring Boot Server Running

<img width="745" height="391" src="https://github.com/user-attachments/assets/9d244f6d-a30b-4249-813b-c4f364ef88ce" />

---

## 🔧 Git Repository Push

<img width="505" height="351" src="https://github.com/user-attachments/assets/ea3316d3-86d2-4d74-bd2d-7a32dfd28682" />

---

## 👩‍💻 Author

**Shivali**

GitHub Profile:
https://github.com/Shivi714
