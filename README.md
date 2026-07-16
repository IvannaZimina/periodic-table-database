# Periodic Table Database

This project is a relational database and a bash-based CLI tool designed to manage and query information about chemical elements. It was developed as part of the "Relational Database" certification curriculum at freeCodeCamp.

## Project Overview
The project involves:
- **Database Normalization:** Fixing existing database structures, adding constraints, and creating relationships between tables.
- **Data Management:** Populating the database with specific chemical element data and ensuring data integrity.
- **Scripting:** Creating a bash script (`element.sh`) that provides a user-friendly interface to search for element details.
- **Version Control:** Managing the project development using Git with structured commit messages.

## Features
- Search for elements by **atomic number**, **symbol**, or **name**.
- Returns comprehensive details: atomic number, name, symbol, type, atomic mass, melting point, and boiling point.
- Handles non-existent entries with a user-friendly error message.

## Usage
1. **Restore the database:**
   ```bash
   psql -U postgres < periodic_table.sql