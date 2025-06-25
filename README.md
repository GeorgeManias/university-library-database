# university-library-database
Database design and implementation project for a university library system, including ER model, SQL schema, sample data, and query examples.

# University Library Database Design and Implementation

This project implements a relational database system for a University Library using SQL. It includes the schema, data population scripts, and key queries to manage and retrieve information about books, students, librarians, loans, and library organization.

## 👨‍💻 Author
**Georgios Manias**  
© 2025 Georgios Manias. All rights reserved.

---

## 📌 Project Overview

The University Library system supports:
- Registration of students and librarians
- Classification of books by category
- Management of physical book copies and their availability
- Loan processing and tracking
- Location management through shelves and corridors

---

## 🗂️ Database Structure

Entities and relationships include:

- **Student**: Registers and borrows book copies.
- **Librarian**: Responsible for managing loans.
- **Book**: Each has one category and many copies.
- **Copy**: A specific physical instance of a book.
- **Shelf**: Indicates physical location in the library.
- **Category**: Describes subject areas.
- **Loan**: Ties a student, librarian, and book copy together.

Refer to `UNIVERSITY LIBRARY_SQL_SCRIPTS.txt` for:
- Table creation
- Sample data insertion

---

## 🔍 Main Features

### 🧾 Queries Implemented

1. **All active loans** with student and librarian details  
2. **Available copies per book**  
3. **Loans registered by a specific librarian**  
4. **Overdue loans** (borrowed more than 2 months ago)  
5. **Books with longest average loan time**

Refer to the Word document for detailed SQL query explanations.

---

## 🏁 Getting Started

### Requirements
- MySQL 8.0 or compatible RDBMS

### Setup Steps

1. Create the database:
   ```sql
   CREATE DATABASE UniversityLibrary;
   USE UniversityLibrary;
   ```

2. Run the SQL script `UNIVERSITY LIBRARY_SQL_SCRIPTS.txt` to create tables and populate with data.

---

## 📄 License

This project is licensed to Georgios Manias, 2025. All rights reserved.


