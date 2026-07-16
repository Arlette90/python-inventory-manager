# Python SQLite Inventory Management System

## Project Overview
A modular command-line interface (CLI) application designed to manage book and author records in a local SQLite database. The project focuses on CRUD (Create, Read, Update, Delete) operations while prioritizing secure database interaction.

## Technical Methodology
* **Database Security**: Utilized parameterized queries to mitigate risks of SQL Injection (SQLi) vulnerabilities.
* **Relational Integrity**: Implemented foreign key constraints and cascade updates to maintain data consistency between authors and their book entries.
* **Modular Design**: Employed a dictionary-based control flow for the application menu, improving code maintainability.

## Key Features
* Automatic schema initialization (`init` function).
* Dynamic user input validation.
* Relational data joining between `book` and `shelf_author` tables.

## How to Run
1. Ensure you have Python installed.
2. Clone the repository.
3. Run the script: `python shelf_track.py`
