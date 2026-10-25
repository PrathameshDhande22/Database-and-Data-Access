# Database and Data Access Tutorials

This repository is a simple learning space for databases and the code used to connect to them. It contains examples, practice files, and small tutorials. It is for learning only.

## What is included

- **SQL Server** - SQL basics, practice queries, a Scrum practice file, and the BikeStores sample database.
- **MySQL** - SQL tutorial files and a notebook.
- **MongoDB** - MongoDB shell queries and Python examples.
- **Python** - SQLAlchemy examples, including a local SQLite database.
- **C#** - Entity Framework, Entity Framework Core, and Dapper tutorials.

## Database connectors and languages

You can work with databases using different languages and tools. This repository includes these examples:

| Language | Connector / tool | Used with |
| --- | --- | --- |
| SQL | SQL Server and MySQL query files | SQL Server, MySQL |
| JavaScript | MongoDB Shell | MongoDB |
| Python | SQLAlchemy | SQLite and other SQL databases |
| C# | Entity Framework / Entity Framework Core | SQL Server |
| C# | Dapper | SQL Server |

## Folder guide

- [`Databases/`](Databases/) - Database tutorials and practice files.
  - [`SQL Server/`](Databases/SQL%20Server/) - SQL Server tutorials and sample database scripts.
  - [`MySQL/`](Databases/MySQL/) - MySQL tutorials.
  - [`MongoDB/`](Databases/MongoDB/) - MongoDB queries and examples.
- [`Connectors/`](Connectors/) - Code that connects applications to databases.
  - [`Python/`](Connectors/Python/) - SQLAlchemy tutorials.
  - [`C#/`](Connectors/C%23/) - Entity Framework, EF Core, and Dapper tutorials.

## How to use this repository

1. Pick a database or connector folder.
2. Start with the files named `tutorial1`, `01_...`, or similar.
3. Run SQL files in a database tool such as SQL Server Management Studio or MySQL Workbench.
4. Open `.ipynb` files in Jupyter Notebook or VS Code.
5. For C# projects, open the `.sln` or `.slnx` file in Visual Studio, update the connection string if needed, and run the project.
6. For Python examples, install the required package, for example: `pip install sqlalchemy`.

> Some examples use local database names, sample data, or connection strings. Change them to match your own database before running them.

## Topics covered

- Creating databases and tables
- Adding, reading, updating, and deleting data
- Joins, constraints, views, functions, and stored procedures
- Database-first and code-first approaches
- Migrations and relationships
- Async queries, transactions, and bulk operations
- MongoDB queries and filters

## References

- Learn C# basics: [C-Sharp-Tutorial](https://github.com/PrathameshDhande22/C-Sharp-Tutorial)
- Learn Python basics: [Python Tutorial](https://github.com/PrathameshDhande22/My-tutorial-References/tree/main/Python%20Tutorial)

Feel free to use these files for practice and learning.
