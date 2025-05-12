# 🏥 Hospital Database Management System (DBMS)

The **Hospital Database Management System (DBMS)** is an SQL-based project aimed at efficiently managing hospital operations. It enables streamlined handling of patient records, staff details, appointments, billing, prescriptions, and medical histories, thereby improving overall service delivery and healthcare management.

## 📌 Project Objective

To develop a robust and user-friendly database system that ensures accurate storage, retrieval, and manipulation of various types of healthcare-related data using Structured Query Language (SQL).

## 🚀 Features

- Patient registration and history tracking
- Doctor and staff information management
- Appointment scheduling and tracking
- Billing and invoice generation
- Prescription and medication records
- Real-time data querying and reporting
- Secure and normalized relational database structure

## 🛠️ Tech Stack

- **Database**: MySQL / PostgreSQL / SQLite
- **Query Language**: SQL (Structured Query Language)
- **Tools**: MySQL Workbench / pgAdmin / DBeaver (optional)

## 🗃️ Database Schema Overview

### Tables:
- `Patients` — Stores patient personal and medical information.
- `Doctors` — Contains doctor details including specialization.
- `Appointments` — Links patients to doctors with scheduled dates.
- `Staff` — Stores data about nurses, technicians, and admin staff.
- `Prescriptions` — Records medications prescribed to patients.
- `Billing` — Maintains billing and payment-related data.
- `Departments` — Holds details of various hospital departments.

> The schema is designed with foreign keys and indexing for efficient data retrieval and integrity.

## 📂 Sample SQL Files Included

- `hospital_db_schema.sql`: Contains table creation scripts.
- `hospital_db_inserts.sql`: Sample data for testing.
- `hospital_db_queries.sql`: Common queries (JOINs, aggregations, etc.)

## 🧑‍💻 How to Use

1. **Clone this repository**:
   ```bash
   git clone https://github.com/your-username/hospital-dbms.git
   cd hospital-dbms
