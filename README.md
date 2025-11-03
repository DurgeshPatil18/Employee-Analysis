# Employee-Analysis

# 🧠 Employee Data Analytics using SQL

This project demonstrates the design and analysis of an employee management database using SQL.  
It includes realistic datasets representing departments, job roles, and employees — and over **17 analytical SQL queries** that reveal HR and organizational insights.  
The project emphasizes **relational database**, **data analysis with aggregate functions**, and **JOIN operations** across multiple tables.

---


## 📊 Project Overview

The **Employee Data Analytics using SQL** project aims to analyze workforce information such as salaries, roles, and department distribution using a structured database system.  
It uses real-world-inspired employee data to perform **data analysis, aggregation, and reporting** using SQL queries.

The database consists of **3 main tables**:
1. **Department**
2. **Employee**
3. **Job_Role**

Each employee is linked to a department and a role, enabling multi-level analysis such as department-wise salary averages, role-based pay comparisons, and employee headcount analytics.

---

## 🎯 Objectives

- To design a normalized relational database for employee and department data.
- To perform HR analytics using **SQL aggregate functions** and **JOIN queries**.
- To explore real-world analytical scenarios like:
  - Salary distribution per department
  - Role-based compensation analysis
  - Yearly hiring and employee trends

---

## 

### 🗂️ **Tables**

#### 1️⃣ Department
| Column | Type | Description |
|---------|------|-------------|
| dept_id | INT | Unique department ID |
| dept_name | VARCHAR(50) | Department name (unique) |

#### 2️⃣ Employee
| Column | Type | Description |
|---------|------|-------------|
| emp_id | INT | Employee ID (primary key) |
| name | VARCHAR(100) | Employee full name |
| salary | DECIMAL(10,2) | Employee salary |
| doj | DATE | Date of joining |
| dept_id | INT | Department reference |
| role_id | INT | Job role reference |

#### 3️⃣ Job_Role
| Column | Type | Description |
|---------|------|-------------|
| role_id | INT | Job role ID |
| role_name | VARCHAR(50) | Role title |
| min_salary | DECIMAL(10,2) | Minimum salary range |
| max_salary | DECIMAL(10,2) | Maximum salary range |

---

<!--## Queries Answered 

1️⃣ List all employees with their department ID and role ID.
2️⃣ How many total employees are in the company?
3️⃣ What are the minimum, maximum, and average salaries of all employees?
4️⃣ How many employees are there in each department?
5️⃣ What is the total salary expense per department?
6️⃣ What is the average salary per department?
7️⃣ What is the total salary expense per role?
8️⃣ Which department has the highest average salary?
9️⃣ How many employees joined after 2020?
🔟 What is the minimum salary per department?
11️⃣ What is the maximum salary per department?
12️⃣ How much total salary was paid each year?
13️⃣ What is the distribution of employees across different salary ranges?
14️⃣ What is the average salary per role?
15️⃣ How many employees joined in each month?
16️⃣ (JOIN) What is the total salary and employee count for each department?
17️⃣ (JOIN) What is the average salary for each job role? -->



## Project Outcome

✅ Designed and implemented a complete relational database using SQL
✅ Generated analytical insights from real-world style data
✅ Strengthened understanding of data modeling, joins, and aggregate functions
✅ Prepared detailed PDF documentation and GitHub repository for demonstration

