# Periodic Table Database

This repository contains the solution for the [FreeCodeCamp Relational Database Project](https://www.freecodecamp.org/learn/relational-database/#build-a-periodic-table-database-project), where a PostgreSQL database is created to store and manage data about the periodic table of elements.

## Project Overview

This project includes:
- **Database Schema**: Setting up tables for elements, their properties, and relationships.
- **Data Population**: Inserting detailed information about each element.
- **SQL Queries**: Writing queries to retrieve and manipulate the data.

## Files Included

- `periodic_table.sql`: The SQL script to create the tables and insert the data.
- `queries.sql`: Example queries to interact with the database.

## Getting Started

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Ramesh-kumawat/periodic-table-database.git
    ```
2. **Set Up the Database**:
    - Ensure PostgreSQL is installed.
    - Run the SQL script to set up the database:
      ```bash
      psql -U your_username -f periodic_table.sql
      ```
3. **Run the Queries**:
    - Execute the example queries:
      ```bash
      psql -U your_username -f queries.sql
      ```

## Requirements

- PostgreSQL

## License

This project is licensed under the MIT License.

