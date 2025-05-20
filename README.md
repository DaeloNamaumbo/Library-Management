#  Library Management System

A comprehensive library management system with a relational database to manage books, members, borrowing transactions, and library operations.

## Features

- Book inventory management
- Member registration and management
- Book borrowing and returning
- Reservation system
- Fine calculation for overdue books
- Staff management with role-based access
- Reporting and analytics

## Database Structure

The system uses a relational database with the following tables:
- Books
- Members
- Staff
- Borrowings
- Reservations
- Fines
- Categories
- Book-category relationships

## Installation

```bash
git clone https://github.com/DaeloNamaumbo/Library-Management.git
```

## Database Setup

1. Install MySQL or MariaDB on your system
2. Run the SQL scripts in the following order:

```bash
mysql -u username -p < library_management.sql
mysql -u username -p library_management < sample_data.sql
```

## Usage

### Book Management
- Add, edit, and remove books from the library inventory
- Track total and available copies
- Categorize books by genre

### Member Management
- Register new members
- Track membership status and expiration
- View borrowing history

### Borrowing Operations
- Check out books to members
- Process returns
- Calculate and collect fines for overdue books
- Reserve books that are currently unavailable

## Sample Queries

The system includes predefined queries for common operations:
- Finding overdue books
- Checking available books
- Viewing member borrowing history
- Calculating fines
- Identifying popular books

## Stored Procedures

Built-in procedures simplify common operations:
- Borrowing books
- Returning books
- Processing fines

