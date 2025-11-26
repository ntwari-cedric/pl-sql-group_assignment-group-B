# pl-sql-group_assignment-group-B

## PHS2 – PL/SQL Assignment  

---

## 👥 Group Members

1. **Ntambara Shema Chrispin** – 28280  
2. **Munyanturire Kaliza Liesse** – 28410  
3. **Himba Aimee Mireille** – 28220  
4. **Ntwari Cedric** – 28228  
5. **Singizwa Boncoeur** – 28228  
6. **Irembere Olivier** – 28392  
7. **Uwase Sonia Umutoni** – 28352

# 📘 **AUCA System Access Control – Database Trigger Module**
AUCA)**.
The system enforces strict operational rules and logs violations for audit and security purposes.

---

## 📌 **Project Overview**

AUCA requires that students and system users can only access academic systems:

* **Monday–Friday**
* **Between 08:00 AM and 05:00 PM**
* **No access allowed during Sabbath (Saturday & Sunday)**

This repository provides a **modular database solution** using:

* ✔ **One function** that encapsulates the business rules
* ✔ **Two triggers** (as required by the specification)

  * Trigger 1 → **Blocks unauthorized operations**
  * Trigger 2 → **Logs all violations for auditing**

This ensures **real-time enforcement** and **traceability** of all unauthorized access attempts.

---

## 🛠 **System Architecture**

### **1. Tables**

The system consists of three core tables:

| Table             | Purpose                                       |
| ----------------- | --------------------------------------------- |
| `student`         | Stores student identity (ID + name)           |
| `student_records` | Operational table students attempt to modify  |
| `access_log`      | Stores all blocked actions for audit tracking |


