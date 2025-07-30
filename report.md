#  Database Course Documentation

## 1.  Comparison: Flat File Systems vs. Relational Databases

| Feature         | Flat File System                         | Relational Database                          |
|----------------|------------------------------------------|----------------------------------------------|
| Structure       | Simple files like CSV or TXT             | Tables with rows and columns (Schema-based)  |
| Data Redundancy | High – repeated data across files        | Low – normalized, less duplication           |
| Relationships   | No direct relationships                  | Tables can relate using foreign keys         |
| Example Usage   | Basic log files, spreadsheets            | Banking systems, HR systems                  |
| Drawbacks       | Poor scalability, difficult querying     | Complex setup, requires DBMS software        |

ERD vs flat file
<img width="607" height="505" alt="image" src="https://github.com/user-attachments/assets/9948c233-b94c-444b-963c-4c5b29f2555c" />

## 2.  DBMS Advantages – Mind Map
<img width="1920" height="1080" alt="MIND MAP" src="https://github.com/user-attachments/assets/bc888bb8-241b-4d43-a51d-c98fbfa9d4d9" />


## 3.  Roles in a Database System

### • System Analyst
Analyzes business needs and translates them into technical requirements. Acts as a bridge between business and technical teams.

### • Database Designer
Designs the structure of the database – tables, keys, constraints – ensuring it supports the system's needs efficiently.

### • Database Developer
Implements the database structure and writes SQL queries, stored procedures, triggers, and other logic.

### • Database Administrator (DBA)
Maintains the database: performance tuning, backups, security, updates, and user access.

### • Application Developer
Integrates the database with applications, writing code that fetches, updates, and manages data.

### • BI Developer
Creates dashboards and reports by analyzing large volumes of data to help decision-makers.


## 4.  Types of Databases

### 🔸 Relational Databases
- **Definition:** Store data in structured tables.
- **Example:** MySQL, PostgreSQL, Oracle
- **Use Case:** Banking, ERP systems

### 🔸 Non-Relational Databases
- **Definition:** Schema-less, can store documents, key-value pairs, etc.
- **Examples:** MongoDB (document), Cassandra (wide-column)
- **Use Case:** Social media feeds, IoT, unstructured data

### 🔸 Centralized Databases
- **Description:** All data stored in a single location
- **Use Case:** Legacy systems in small businesses

### 🔸 Distributed Databases
- **Description:** Data spread across multiple physical locations
- **Use Case:** Multinational applications with low-latency needs

### 🔸 Cloud Databases
- **Description:** Hosted on cloud platforms, managed by providers
- **Use Case:** Modern web apps, SaaS platforms


## 5.  Cloud Storage & Databases

###  What is Cloud Storage?
Cloud storage allows saving data on remote servers accessed via the internet. It supports database backups, scalability, and remote access.

###  How It Supports Databases
- Automatically scalable and redundant
- High availability and global access
- Easy backup/restore and maintenance

###  Advantages of Cloud Databases
- **Scalability:** Grows with user demand
- **Managed Services:** Reduced admin work
- **Availability:** 99.9% uptime with geo-replication

#### Examples:
- **Amazon RDS** – Managed relational DB
- **Google Cloud Spanner** – Globally distributed SQL DB
- **Azure SQL** – Fully managed MS SQL

###  Disadvantages
- Data security concerns
- Potential latency
- Vendor lock-in risks
- Cost can grow with scale


##  Conclusion
This report highlights core concepts in database systems including the transition from flat files to relational systems, roles involved, types of databases, and the evolution into cloud-hosted solutions.

