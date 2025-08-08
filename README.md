# Java To-Do List Application (Servlets + JSP + MySQL)

This is a full-stack Java web application for managing personal tasks.  
It is built using **Java Servlets**, **JSP**, and **MySQL** with JDBC for database connectivity.

## Features
- **User Registration & Login** – Securely store user details in MySQL.
- **Add Tasks** – Create new tasks with name, date, and status.
- **View Tasks** – Display tasks for the logged-in user.
- **Mark Tasks as Completed** – Update task status using SQL `UPDATE` queries.
- **Session Management** – Maintains login state using HTTP sessions.

## Technologies Used
- **Backend:** Java Servlets, JSP, JDBC
- **Frontend:** HTML, CSS, JSP
- **Database:** MySQL
- **Server:** Apache Tomcat

## Database Schema
**Tables:**
- `register` – Stores user details.
- `tasks` – Stores user tasks.
- `taskid_pks` – Tracks latest task ID per user.

## SQL Skills Demonstrated
- Creating tables with relational mapping
- Performing CRUD operations (`INSERT`, `SELECT`, `UPDATE`, `DELETE`)
- Using `PreparedStatement` for SQL injection prevention
- Transaction handling (`commit`/`rollback`) for multi-step operations

## Setup Instructions
1. Create a MySQL database `sbb3_todo` and run the provided SQL schema.
2. Update database credentials in `DBConn.java`.
3. Deploy the project on Apache Tomcat.
4. Access the app via `http://localhost:8080/sbb3_todo`.

---
