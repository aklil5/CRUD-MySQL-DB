# CRUD with MySQL

A simple CRUD (Create, Read, Update, Delete) application built with Express and MySQL. It lets users add, list, edit, and delete records containing a name, address, and company information. The front end, server, and database logic live together in a single project, built to practice how a web page talks to a database.

## Features

- **Create:** Add a new record (name, address, company information)
- **Read:** List all saved records
- **Update:** Edit an existing record
- **Delete:** Remove a record
- Data stored in a MySQL database

## Tech Stack

- **Front end:** HTML, CSS, JavaScript
- **Server:** Node.js and Express
- **Database:** MySQL, run locally with MAMP

## Data Fields

| Field | Description |
|-------|-------------|
| `id` | Auto-generated unique ID |
| `name` | Person's name |
| `address` | Address |
| `company_info` | Company information |

## Project Structure

```
CRUD-MySQL-DB/
├── insert_select_update_delete/   # Project code: server, database queries, and front end
└── .gitignore
```

## What I Practiced

- Connecting Node.js and Express to a MySQL database
- Writing SQL `INSERT`, `SELECT`, `UPDATE`, and `DELETE` queries
- Building routes that handle each CRUD operation
- Sending form data from a web page to the server and displaying results
- Running a local MySQL database with MAMP

## Getting Started

1. Start MAMP and make sure the MySQL server is running.
2. Create a database and table in phpMyAdmin that match the fields above.
3. In `insert_select_update_delete`, run `npm install`.
4. Add your MAMP database settings (host, port, user, password, database name) in the project's connection file
5. Start the server with `node index.js` (or your main file's name) and open the local address shown in the terminal.

