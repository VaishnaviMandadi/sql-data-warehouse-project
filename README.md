# sql-data-warehouse-project
Building a modern data warehouse with SQL server, including ETL processes, data modeling and analytics.

# SQL Data Warehouse Project

This repository contains my hands-on implementation of a **SQL Data Warehouse**, built while following the YouTube tutorial series by **Data With Baraa**.

I am working through the project step by step and committing changes as I progress, using this repository to document my learning and practical understanding of data warehousing concepts.

---

## Project Purpose

The purpose of this project is to:

* Learn core **data warehousing fundamentals**
* Understand how to design and implement a **star schema**
* Build **fact and dimension tables** using SQL
* Practice real-world **ETL / ELT workflows**
* Apply clean, readable SQL suitable for analytics and reporting

---

## Reference

* **YouTube Tutorial**: SQL Data Warehouse Project by Data With Baraa
* **Original Repository**: [https://github.com/DataWithBaraa/sql-data-warehouse-project](https://github.com/DataWithBaraa/sql-data-warehouse-project)

This repository is my own implementation created for learning and practice.

---

## High-Level Architecture

```
Source Data
   ↓
Staging Tables
   ↓
Data Warehouse (Star Schema)
   ↓
Analytics & Reporting
```

---

## Data Warehouse Design

* Schema type: **Star Schema**
* Fact tables store measurable business data
* Dimension tables store descriptive attributes such as time, customers, and products

The design follows the structure introduced in the tutorial and evolves as the project progresses.

---

## Repository Structure

```
sql-data-warehouse-project/
│
├── data/        # Source data files
├── staging/     # Staging tables and transformations
├── warehouse/   # Fact and dimension tables
├── scripts/     # SQL scripts (DDL, DML, transformations)
├── docs/        # Notes and documentation
└── README.md
```

Folder structure may change as new concepts are introduced.

---

## Tools Used

* SQL
* Relational Database (as used in the tutorial)
* Git & GitHub for version control

---

## How to Use This Repository

1. Clone the repository

   ```bash
   git clone https://github.com/<your-username>/sql-data-warehouse-project.git
   ```
2. Review commits in order to follow the project build step by step
3. Refer to SQL scripts alongside the tutorial videos

---

## Project Status

* **In progress**
* Updated continuously as I move through the tutorial

---

## Credits

* Tutorial by **Data With Baraa**

This project is created for educational purposes and personal learning.

