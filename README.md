# :sparkles: Database

> Definition:

- A database is a data structure that stores organized information. Most databases contain multiple tables, which may each include several different fields. 

- A database is a collection of related information stored in one or more computer files in an organized fashion. Normally the information or data is organized into tables. The information in a table is organized in such a way that it can easily be updated, sorted, corrected, and filtered.


>Structure of a Database:
 
 The database is made up of tables that contain columns and rows. Data is separated by categories into tables in order to avoid duplication.

- Table
- Row   ---> Record
- Column
- Cell  ---> Field

> Relations

The tables in a relational database are linked through a key.

This is an ID in each table that uniquely identifies a row.

Each table has a **primary key** column, and any table that needs to link to that table will have a **foreign key** column whose value will match the first table's primary key.

> Type of Relations

- **One-to-One :** A row in table (A) can have only one matching row in table (B), and vice versa.
- **One-to-Many (or Many-to-One) :** A row in table (A) can have many matching rows in table (B), but a row in table (B) can have only one matching row in table (A).
- **Many-to-Many :** A row in table (A) can have many matching rows in table (B), and vice versa.
- **Self-Referencing Relationships :** An **one-to-one** relationship exists when a given record in the table can be related to only one other record within the table.

> Queries

A database query extracts data from a database and formats it in a readable form. A query must be written in the language the database requires; usually, that language is **Structured Query Language (SQL)**.

### Asala Matarya :see_no_evil: :wink:
