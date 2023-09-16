# Database Engine with Octree Indices

## Introduction
Welcome to the Database Engine with Octree Indices project! This project is designed to showcase a small database engine with support for Octree Indices. It's built as part of the CSEN604: Database II course at the German University in Cairo.

## Overview
- **Programming Language:** Java
- **Development Environment:** Eclipse, IntelliJ, or NetBeans

## Project Description
In this project, we've implemented a simplified database engine with Octree Index support. Here's a brief overview of the key features:

### Tables
- Tables are stored as pages on disk, with each page as a separate file.
- Supported column types include Integer, String, Double, and Date (in "YYYY-MM-DD" format).

### Indices
- Octree indices are used to improve query performance.
- Indices are created on-demand and updated when new data is added or removed.
- They are saved to disk and loaded during application startup.
- Indices are used to speed up query execution.

## How to Use
1. Initialize the database engine using the `init()` method.
2. Create tables using `createTable(...)`.
3. Create Octree indices using `createIndex(...)`.
4. Insert data into tables with `insertIntoTable(...)`.
5. Update existing records using `updateTable(...)`.
6. Delete rows from tables with `deleteFromTable(...)`.
7. Perform queries with `selectFromTable(...)`.
8. The application can be configured via the `DBApp.config` file in the `resources` directory.

## Directory Structure
- `DBApp.config`: Configuration file for the application.

## Getting Started
1. Clone the repository.
2. Import the project into your preferred Java IDE (Eclipse, IntelliJ, or NetBeans).
3. Run the project.

## Contributors
- [Your Name]
- [Teammate 1]
- [Teammate 2]
- [Teammate 3] (if applicable)

Feel free to explore and use this database engine for your projects. If you have any questions, please refer to the project documentation.

Happy coding!
