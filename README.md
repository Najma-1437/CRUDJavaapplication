# Student Records CRUD Application (Java + PostgreSQL)

This is a simple Java console application that demonstrates basic CRUD operations  
(Create, Read, Update, Delete) using a PostgreSQL database.

## Group Members
- Najma
- Hafswa
- Mahir
- Patrick
- Shifla
  



## CRUD PROPERTIES

-  Add new student records
-  View all students
-  Update existing student details
-  Delete student records
-  Connects to PostgreSQL using JDBC
-  Uses properties file (`db.properties`) for secure DB access

---

##  Tech Stack

- Java 17+
- PostgreSQL
- JDBC
- IntelliJ IDEA
- GitHub

---

##  How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/student-crud.git
cd student-crud

## 2. Create a PostgreSQL database called studentdb, and run this SQL:
CREATE TABLE students (
  id SERIAL PRIMARY KEY,
  name VARCHAR(100),
  email VARCHAR(100),
  course VARCHAR(100)
);
## 
3. Create a db.properties file in the project root:
db.url=jdbc:postgresql://localhost:5432/studentdb
db.user=your_username
db.password=your_password

