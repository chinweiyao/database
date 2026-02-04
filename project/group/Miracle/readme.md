# 🚗 Hasta Car Rental System Database Project 📊

> **Course**: SECP2523 – Database (WBL)  
> **Session**: Semester I 2025/2026  
> **Section**: 02  
> **Lecturer**: PM Dr. Mohd Shahizan Othman  
> **Industry Stakeholder**: Hasta Travel & Tours Sdn. Bhd.

---

## 👥 Team Miracle

### Members
| Name | Matric ID | Role |
| :--- | :--- | :--- |
| **Chew Jie Sheng** | A24CS0059 | Team Leader |
| **Chin Wei Yao** | A24CS0234 | Member |
| **Kavivarthan A/L Mannivanan** | A24CSXXXX | Member |
| **Aman Sufian Shah Bin Shamsuddin** | A24CSXXXX | Member |

---

## 📖 Project Overview

This project focuses on the **analysis, design, and implementation of a centralized relational database system** for **Hasta Travel & Tours Sdn. Bhd.**, a car rental service provider operating within Universiti Teknologi Malaysia (UTM).
Previously, the company relied on **manual and fragmented workflows**, including WhatsApp messages, handwritten forms, Excel spreadsheets, and physical whiteboards. These practices caused inefficiencies, data redundancy, and difficulties in tracking rentals and generating reports.
The proposed system replaces these manual processes with a **structured, secure, and database-driven solution** to improve operational efficiency, data accuracy, and decision-making.

---

## 🔹 Phase 1 – Project Proposal
> **Phase 1** identifies existing problems and proposes a database-based solution.

### 🚩 Problem Statement
The current car rental operation uses manual methods:
- 📱 **Booking** handled via WhatsApp messages  
- 📋 **Car availability** tracked on whiteboards  
- 📁 **Records** stored in handwritten forms and Excel files  

**Key Issues**:
- ❌ High risk of data redundancy and human error  
- ❌ Slow and inefficient booking approval process  
- ❌ Difficulty in tracking rental history and revenue  

### 💡 Proposed Solution
A **Centralized Relational Database System** that:
- ✅ Automates booking validation and approval  
- ✅ Tracks car availability in real time  
- ✅ Securely stores customer data and documents  
- ✅ Generates automated reports and analytics  

**System Scope**:
- **Customer Module**: Registration, booking, payment, and profile management  
- **Staff Module**: Booking approval, car management, and return inspection  
- **Admin Module**: Staff management, analytics dashboard, and reporting  

---

## 🔹 Phase 2 – Database Conceptual Design
> **Phase 2** translates system requirements into a conceptual data model.

### 📐 Design Artifacts
- **Data Flow Diagram (DFD)**  
  Illustrates data flow between Customers, Staff, Admin, and system processes such as booking, payment, and inspection.

- **Entity Relationship Diagram (ERD)**  
  Defines core entities including:
  - `User`
  - `Customer`
  - `Staff`
  - `Car`
  - `Rental`
  - `Payment`
  - `Voucher`
  - `Penalty`

- **Enhanced ERD (EERD)**  
  Implements specialization where `User` is generalized into `Customer` and `Staff` to improve data organization and reduce redundancy.

### 📜 Key Business Rules
- A car cannot be double-booked for overlapping rental periods  
- Cars require a cooldown period after return for inspection and cleaning  
- Loyalty stamps are awarded based on rental duration  
- Late returns incur penalty charges based on delay duration  

---

## 🔹 Phase 3 – Logical Design & Implementation

> **Phase 3** focuses on normalization, logical design, and SQL implementation.

### ⚙️ Logical Design & Normalization
- All relations were normalized up to **Third Normal Form (3NF) / BCNF**  
- Functional dependencies were analyzed to eliminate redundancy  
- Logical ERD was derived from conceptual design and business rules  

### 🛠️ Database Implementation
- **DDL (Data Definition Language)**  
  - Tables created with Primary Keys and Foreign Keys  
  - Constraints applied using `NOT NULL`, `UNIQUE`, and `ON DELETE CASCADE`

- **DML (Data Manipulation Language)**  
  - SQL queries for data insertion, update, deletion  
  - Reporting queries such as total revenue and rental history  

- **Integrity Control**
  - Referential integrity enforced  
  - Cascading rules applied for related records  

---

## 🎯 Conclusion

This project demonstrates how a **well-designed database system** can significantly improve efficiency, accuracy, and scalability in a real-world car rental business. By replacing manual workflows with a centralized database, Hasta Travel & Tours Sdn. Bhd. can achieve better data management, operational control, and reporting capabilities.
<p align="center">
  <i>"Transforming manual processes into a structured digital solution."</i>
</p>

