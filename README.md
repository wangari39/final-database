# Library Management System

## Project Overview
This project is a **Library Management System** database designed using MySQL. It provides a relational schema to manage authors, books, members, loans, and categories within a library. The database supports tracking book information, author details, member registrations, loan transactions, and categorization of books.


## Features
 Store and manage authors with their bios.
 Manage books with unique ISBNs and published year.
 Handle many-to-many relationships between books and authors.
 Track members with contact information.
 Record loans with loan and return dates.
 Organize books into categories, supporting multiple categories per book.

---

## Database Schema
The database includes the following tables:

   Authors**: Information about book authors.
  Books**: Details of books available in the library.
  BookAuthors**: Many-to-many relationship between books and authors.
  Members**: Library members who can borrow books.
  Loans**: Records of book loans to members.
  Categories**: Book categories (e.g., Fiction, Science).
  BookCategories**: Many-to-many relationship between books and categories.





