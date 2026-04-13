
# Assignment 5

## Part 1: ERD Diagram

<img width="1201" height="411" alt="ERD Diagram" src="https://github.com/user-attachments/assets/d68fc944-9374-4b64-84f1-b366a983aaf0" />

## Part 2: Mapping

Database Schema Mapping: User & Product System

Table: User
-----------------------------------
- ID (integer) [Primary Key]
- firstName (varchar)
- lastName (varchar)
- email (varchar)
- role (varchar)
- password (varchar)

Table: Product
-----------------------------------
- id (integer) [Primary Key]
- name (varchar)
- stock (integer)
- isDeleted (bool)
- price (integer)
- user_id (integer) [Foreign Key referencing User.ID]

Table: User_Phone
-----------------------------------
- phone_number (varchar) [Primary Key]
- user_id (integer) [Primary Key, Foreign Key referencing User.ID]

<img width="620" height="570" alt="Mapping" src="https://github.com/user-attachments/assets/7a18c30b-529c-435a-a473-a64b9b3fa786" />
