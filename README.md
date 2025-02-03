# **SQL Challenge – Employee Database Analysis**

## **Overview**
This project focuses on analyzing historical employee data from **Pewlett Hackard**, a fictional company. The challenge involves designing a **relational database**, importing employee records, and running SQL queries to extract insights about employees, departments, salaries, and managers.

## **Repository Location**
🔗 [GitHub Repository](https://github.com/laghayeva/sql-challenge)

## **Project Tasks**
The challenge is divided into three main sections:

### **1. Data Modeling**
- Designed a **relational database schema** based on six CSV files.
- Created an **Entity Relationship Diagram (ERD)** to define table relationships.

### **2. Data Engineering**
- Created a **PostgreSQL database** named `employees_db`.
- Defined table schemas using `CREATE TABLE` statements with **primary keys, foreign keys, and constraints**.
- Imported employee data from CSV files into the database.

### **3. Data Analysis**
- Executed SQL queries to retrieve insights, including:
  - Employee details and salaries.
  - Hiring trends.
  - Department managers.
  - Department-wise employee distribution.
  - Most common last names among employees.

## **Database Schema**
The database consists of six tables:

| Table Name    | Description |
|--------------|------------|
| `employees`  | Stores employee details, including name, birthdate, sex, and hire date. |
| `departments` | Contains department names and unique department IDs. |
| `titles` | Stores job titles associated with employees. |
| `salaries` | Tracks employee salaries. |
| `dept_emp` | Links employees to their respective departments. |
| `dept_manager` | Identifies managers assigned to each department. |
