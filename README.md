# Library Management System (SQL)

A MySQL database implementation for a simple Library Management System created by Harshdeep (`25BAI70686`).

## Overview
This repository contains database definitions, constraints, operations, and queries for managing library members and books.

### Features Included
1. **Schema Creation**: `library_magsystem` database.
2. **Table Design**:
   - `Member`: Primary key, auto-increment, unique email & phone, default membership type.
   - `Book` / `Library_book`: Primary key, foreign key linking to `Member`, constraints, default availability.
3. **Data Operations**:
   - Insert records for members and books.
   - Filter books by category (`SELECT`).
   - Update book availability status (`UPDATE`).
   - Remove books by ID (`DELETE`).
   - Alter table structure to add a publisher column (`ALTER`).
   - Rename table to `Library_book` (`RENAME`).

## Files
- `Harshdeep_25BAI70686.sql`: Complete SQL script containing schema and queries.
