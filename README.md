# 🏥 Hospital Management System (Java + JDBC + MySQL)

A simple **console-based hospital management system** built using **Java, JDBC, and MySQL**, designed to manage patients, doctors, appointments, and billing operations.

---

## 🚀 Features

- ✅ Add, View Patients
- ✅ Doctor Management (extendable)
- ✅ Appointment Scheduling (extendable)
- ✅ Billing Module (optional add-on)
- ✅ View Records in Tabular Format
- ✅ JDBC + MySQL Integration
- ✅ Console Input Handling with Java Scanner
- ✅ Error Handling with Try-Catch Blocks

---

## 🧰 Technologies Used

| Technology | Purpose                |
|------------|------------------------|
| Java       | Core application logic |
| JDBC       | Database connectivity  |
| MySQL      | Backend database       |
| IntelliJ   | Development IDE        |
| GitHub     | Version control        |

---

## 🧱 Database Schema (patients table)

```sql
CREATE TABLE patients (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    age INT,
    gender VARCHAR(20)
);
🙋‍♂️ Author
Prankul Goyal
🎓 B.Tech CSE | Java Developer | Frontend Enthusiast
📧 goyalprankul27@gmail.com

