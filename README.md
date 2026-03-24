# Spring Boot Student CRUD API

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

###  STEP 1: Check Empty (GET)


<img width="565" height="350" alt="{7DEFEF17-42D3-43E9-AC2F-884642FC8CDB}" src="https://github.com/user-attachments/assets/7a90140d-76e9-4c2e-accb-d1215e21ab72" />


```

###  STEP 2: POST (Add Student)
```
<img width="570" height="426" alt="{0A976E8E-C47E-4BDF-AD31-4AF68ED1386B}" src="https://github.com/user-attachments/assets/a6b8b543-c91e-4230-ab5b-65b5a230d752" />

```
### STEP 3: GET (Check Data)
```
<img width="566" height="477" alt="{277996D4-A61C-44AD-884B-3463053733DA}" src="https://github.com/user-attachments/assets/e9159e85-8641-4bf8-9977-4abdb69d2f06" />
```
###  STEP 4: PUT (Update Student)

```
POST /api/students

<img width="565" height="460" alt="{465014D8-B22A-4B06-9603-88316AF1A209}" src="https://github.com/user-attachments/assets/1859ac76-c983-4918-98d2-95f820ea5d3c" />

```

STEP 5: GET (Check Update)
```

<img width="570" height="455" alt="{73F6BA4E-CEF8-43DD-B158-254660F93D9E}" src="https://github.com/user-attachments/assets/c9f9d931-db47-471a-af44-e80dd2df72cc" />

```

STEP 6: DELETE Student
```
<img width="561" height="390" alt="{1DC4C1BE-BA35-41B8-BA17-2E3C5E991CC6}" src="https://github.com/user-attachments/assets/d6593aad-8b9a-46a7-a56c-1fdb050c4421" />

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

1zw---

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


# 🚀 Spring Boot Student CRUD API

## 📌 Project Description

This project is a **Spring Boot REST API** that performs complete **CRUD operations (Create, Read, Update, Delete)** for managing student data using **Spring Boot, Spring Data JPA, and MySQL**.

The API allows users to:

* Add a new student
* View all students
* View a student by ID
* Update student details
* Delete a student

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

# 🔗 API Testing Steps (Postman)

## 🔹 STEP 1: Check Empty (GET)

```
GET /api/students
```

<img width="565" height="350" src="https://github.com/user-attachments/assets/7a90140d-76e9-4c2e-accb-d1215e21ab72" />

---

## 🔹 STEP 2: Add Student (POST)

```
POST /api/students
```

<img width="570" height="426" src="https://github.com/user-attachments/assets/a6b8b543-c91e-4230-ab5b-65b5a230d752" />

Example Request:

```
{
"name": "Shivali",
"email": "shivali@gmail.com"
}
```

---

## 🔹 STEP 3: Check Data (GET)

```
GET /api/students
```

<img width="566" height="477" src="https://github.com/user-attachments/assets/e9159e85-8641-4bf8-9977-4abdb69d2f06" />

---

## 🔹 STEP 4: Update Student (PUT)

```
PUT /api/students/{id}
```

<img width="565" height="460" src="https://github.com/user-attachments/assets/1859ac76-c983-4918-98d2-95f820ea5d3c" />

---

## 🔹 STEP 5: Check Updated Data (GET)

```
GET /api/students
```

<img width="570" height="455" src="https://github.com/user-attachments/assets/c9f9d931-db47-471a-af44-e80dd2df72cc" />

---

## 🔹 STEP 6: Delete Student

```
DELETE /api/students/{id}
```

<img width="561" height="390" src="https://github.com/user-attachments/assets/d6593aad-8b9a-46a7-a56c-1fdb050c4421" />

---

## 🔹 GET by ID

```
GET /api/students/{id}
```

<img width="570" height="425" src="https://github.com/user-attachments/assets/5fa18ec4-df8b-409c-b6e8-3a780ba0bfb1" />

---

# 📷 Output Screenshots

## 🌐 API Output in Browser

<img width="960" height="218" src="https://github.com/user-attachments/assets/6a59a914-f681-4d5a-a7a3-15816cb0a2b5" />

---

## 📄 Example API Response

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

## ▶️ Running the Project

1. Clone the repository

```
git clone https://github.com/Shivi714/Full-Stack-exp-7.git
```

2. Open in Eclipse IDE

3. Run

```
Exp7Application.java
```

4. Open

```
http://localhost:8080/api/students
```

---

## 👩‍💻 Author

**Shivali**

🔗 GitHub Profile:
https://github.com/Shivi714
