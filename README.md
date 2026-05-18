<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a1628,40:1a3a5c,70:1e5f8e,100:0a1628&height=200&section=header&text=PayrollDB&fontSize=68&fontColor=ffffff&fontAlignY=38&fontStyle=bold&desc=Complete%20Payroll%20Management%20System%20in%20MySQL&descSize=16&descAlignY=62&descColor=7eb8f7" width="100%"/>

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/ERD-Designed-1e5f8e?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/SQL-Stored%20Procedures-orange?style=for-the-badge"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Includes-ERD%20Diagram-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/Features-Payslips%20%7C%20Tax%20%7C%20Attendance-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Type-Database%20Design%20Project-gray?style=flat-square"/>
</p>

<br/>

> **PayrollDB** is a comprehensive MySQL relational database system for managing employee payroll — covering employee records, attendance tracking, salary calculation, tax deductions, and automated payslip generation, all designed with a formal ERD and implemented in clean SQL.

</div>

---

## 🗄️ What This Covers

| Module | Description |
|---|---|
| 👤 **Employee Management** | Employee records, departments, designations, joining dates |
| 📅 **Attendance Tracking** | Daily attendance, leave types, leave balances |
| 💰 **Salary Calculation** | Basic pay, allowances, overtime, deductions computed automatically |
| 🧾 **Tax Deductions** | Tax slabs applied per employee salary bracket |
| 📄 **Payslip Generation** | Monthly payslip records per employee per period |

---

## 📊 Database Design

The full Entity Relationship Diagram is included in the repository:

📎 **[ERD Payroll System.pdf](./ERD%20Payroll%20System.pdf)**

Key entities and relationships:

```
Employee ──< Attendance
Employee ──< Salary
Employee ──< Payslip
Employee >── Department
Employee >── Designation
Salary ──< TaxDeduction
Salary ──< Allowance
```

---

## 🚀 Setup

### 1. Clone the repository

```bash
git clone https://github.com/mahmedmajeedai/Payroll-Management-System-in-MySQL.git
```

### 2. Import the SQL schema

```bash
mysql -u root -p < "Payroll Management System.sql"
```

### 3. Open in MySQL Workbench or any SQL client

Connect to your local MySQL instance and the schema will be ready to query.

---

## 📁 Files

| File | Purpose |
|---|---|
| `Payroll Management System.sql` | Complete database schema — tables, relationships, procedures, sample data |
| `ERD Payroll System.pdf` | Entity Relationship Diagram showing full schema design |

---

## 🔧 Key SQL Concepts Used

- Normalised relational schema (3NF)
- Foreign key constraints and cascades
- Stored procedures for salary calculation
- Views for payslip generation
- Triggers for attendance-based deductions
- Indexed columns for performance on large employee datasets

---

<div align="center">

**Built by [Muhammad Ahmed Majeed](https://github.com/mahmedmajeedai)**

*Relational database design for enterprise payroll management*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e5f8e,50:1a3a5c,100:0a1628&height=80&section=footer" width="100%"/>

</div>
