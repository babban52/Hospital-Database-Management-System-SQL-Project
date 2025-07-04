# 🏥 Hospital-Database-Management-System-SQL-Project

## 📋 Project Overview

This project presents a **Relational Database Management System (RDBMS)** for a hospital to handle core medical and administrative activities efficiently. It digitizes hospital workflows such as patient care, appointments, medication management, physician scheduling, room availability, and more.

Hospitals face the challenge of maintaining a vast amount of daily records — this system helps by organizing those into structured, queryable tables.

---

## 🛠️ Technologies Used

- **Database**: MySQL
- **Language**: SQL (Structured Query Language)
- **Tools**: ER Diagram Tool (e.g., dbdiagram.io, Lucidchart), MS Word, VS Code

---

## 🗃️ Database Schema

### Key Tables:

- **Physician**
- **Department**
- **Affiliated_With**
- **Procedure**
- **Trained_In**
- **Patient**
- **Nurse**
- **Appointment**
- **Medication**
- **Prescribes**
- **Block**
- **Room**
- **On_Call**
- **Stay**
- **Undergoes**

Each table contains relevant fields with appropriate primary and foreign keys to maintain referential integrity.

### Example: `Physician` Table

| Column      | Type     | Description                         |
|-------------|----------|-------------------------------------|
| employeeid  | INT (PK) | Unique ID of physician              |
| name        | TEXT     | Name of the physician               |
| position    | TEXT     | Position/designation                |
| ssn         | TEXT     | Social Security Number              |

---

## 🔁 ER Diagram

A complete ER diagram is available to visualize relationships among entities like patients, nurses, physicians, procedures, and rooms.  
![ER Diagram](./images/er_diagram.png)

---

## 📊 SQL Query Set

Includes 39 real-world hospital queries such as:

1. Find all unregistered nurses.
2. Identify department heads.
3. Count appointments per patient.
4. Check room availability by block/floor.
5. List patients who were treated by uncertified physicians.

These queries help simulate complex data operations required in hospital analytics, administration, and auditing.

---

## ✅ Key Features

- Detailed relational schema for healthcare operations
- Tracks room availability, staff scheduling, and treatment history
- Maintains physician training and certification records
- Rich set of SQL queries for data extraction and reports
- Enforces data integrity using composite keys and foreign constraints

---

## 📁 Project Structure

Hospital-Database/
├── schema.sql # SQL table creation scripts
├── sample_data.sql # Sample insert queries (optional)
├── queries.sql # SQL queries for use-cases
├── ER_diagram.png # Entity Relationship Diagram
└── README.md # Project documentation

---

## 🚀 Getting Started

1. Create the tables using `schema.sql` in your RDBMS.
2. Insert sample data (optional).
3. Run queries from `queries.sql` to test functionality.
4. Use a GUI (like DBeaver or MySQL Workbench) to visualize schema and outputs.

---

## ✍️ Author

**Debraj Mahato**  
_Data Science & Analytics Professional_  
📫 Reach out for feedback, collaboration, or improvements.

---

## 📌 License

This project is open for educational and non-commercial use. Attribution is appreciated.
