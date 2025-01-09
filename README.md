# Walmart-Sales-Analysis-Project

This repository contains SQL scripts and queries developed to analyze Walmart sales data. The project is aimed at showcasing data analysis skills using SQL and is based on the provided dataset `Walmart Sales Data.csv`.

---

## Project Overview

The project involves analyzing Walmart sales data to derive insights such as:
- Sales trends.
- Performance of products across categories.
- Regional analysis of sales.

### Key Features:
- Use of SQL queries for data extraction and transformation.
- Insights derived through aggregate functions, joins, and subqueries.
- Solutions for common SQL errors (e.g., `LOAD DATA LOCAL INFILE` restrictions).

---

## Files in the Repository

### 1. **Walmart SQL Queries.sql**
This file contains all the SQL scripts and queries used in the project.

### 2. **Walmart Sales Data.csv**
Sample dataset . Replace the path in the SQL scripts with the correct file location when running queries.

---

## Prerequisites

### Software:
- **MySQL**: Ensure MySQL is installed and configured on your system.
- **Database Client**: Tools like MySQL Workbench or any command-line client.

### MySQL Configuration:
To successfully execute `LOAD DATA LOCAL INFILE` commands, enable the `local-infile` option in your MySQL configuration.

#### Server Configuration:
Add the following to your MySQL config file (`my.cnf` or `my.ini`):
```ini
[mysqld]
local-infile=1
```
Restart your MySQL server to apply the changes.

#### Client Configuration:
Use the `--local-infile=1` flag when connecting to MySQL:
```bash
mysql --local-infile=1 -u username -p
```

---

## How to Use the SQL Scripts

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/walmart-sql-project.git
   ```

2. Import the dataset:
   Use the `LOAD DATA LOCAL INFILE` command in `Walmart SQL Queries.sql` to load the data into MySQL.

3. Run the SQL queries:
   Open the `.sql` file in your database client and execute queries to analyze the data.

---

## Common Errors and Fixes

### Error Code: 2068
- **Cause**: `LOAD DATA LOCAL INFILE` command is restricted.
- **Solution**: Enable `local-infile` as described in the Prerequisites section.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact
For questions or collaboration, feel free to reach out:
- Email: [your_email@example.com](mailto:adityagehlot@gmail.com)
- LinkedIn: [Your LinkedIn Profile](https://linkedin.com/in/yourprofile)

---

**Happy Analyzing!**

