# Library-Management-System
# Library Management System using AVL Tree and Hash Tables

## Project Description
This project implements a Library Management System for UET using
efficient data structures. An AVL Tree is used to store book records
indexed by ISBN, while Hash Tables are used for fast searching by
title, author, and member ID.

## Data Structures Used
- AVL Tree (Book Catalog)
- Hash Table with Chaining (Title Index)
- Hash Table with Chaining (Author Index)
- Hash Table with Chaining (Member Database)

## Features
- Add and manage books
- Add and manage members
- Search books by ISBN, title, and author
- Borrow and return books
- Display books in sorted order (by ISBN)

## Borrowing Rules
- A member can borrow a maximum of 5 books
- A book can be borrowed only if copies are available

## File Structure
- avl_tree.py        → AVL Tree implementation
- hash_table.py     → Hash Table with chaining
- library_system.py → Main library system logic
- README.md         → Project documentation

## How to Run
1. Open the project folder
2. Run `library_system.py`
3. Follow console output for operations

## Testing
- Tested with 50 books and 20 members
- Edge cases handled such as unavailable books and borrow limits

## Team Members & Contribution
This project was completed individually by Alina Hassan.

## Notes
- File I/O not implemented
- Data hardcoded for testing
