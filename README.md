# SQL & Data Analysis Study Kit

A free, open-source collection of resources for learning SQL and Excel-based data analysis — from fundamentals to interview-ready practice.

## What's Inside

| File | Description |
|------|-------------|
| [analysis/sql.md](analysis/sql.md) | Complete SQL learning roadmap — database fundamentals, SQL syntax, joins, subqueries, window functions, CTEs, and curated YouTube playlists |
| [analysis/sql-75-questions.md](analysis/sql-75-questions.md) | 75 SQL interview questions organized by 10 key patterns that cover 90% of data analyst interviews |
| [analysis/sql-75-datasets.sql](analysis/sql-75-datasets.sql) | Ready-to-use PostgreSQL script with 17 tables and sample data to practice all 75 questions |
| [analysis/excel-roadmap.md](analysis/excel-roadmap.md) | Excel for data analysis guide — functions, data cleaning, pivot tables, charts, and real-world business applications |

## Getting Started

### SQL Practice

1. Install [PostgreSQL](https://www.postgresql.org/download/)
2. Load the dataset:
   ```bash
   psql -U your_username -d your_database -f analysis/sql-75-datasets.sql
   ```
3. Open `analysis/sql-75-questions.md` and start solving

### SQL Learning Path

Follow the roadmap in `analysis/sql.md`:

1. **Basics** — SELECT, WHERE, CRUD operations, ORDER BY, GROUP BY
2. **Joins** — INNER, LEFT, RIGHT, OUTER, SELF
3. **Aggregations** — SUM, COUNT, AVG, MIN, MAX with GROUP BY and HAVING
4. **Intermediate** — Subqueries, Window Functions (RANK, ROW_NUMBER, LAG/LEAD), CTEs
5. **Practice** — Work through the 75 questions to solidify your skills

### Excel Analysis

Follow `analysis/excel-roadmap.md` covering:
- Core functions (VLOOKUP, SUMIF, COUNTIF, etc.)
- Data cleaning and preparation
- Pivot Tables and data modeling
- Charts and visualization
- Real-world business scenarios

## Topics Covered

- Database fundamentals (DBMS, RDBMS, normalization)
- SQL CRUD operations
- Joins and set operations
- Aggregate and window functions
- Common Table Expressions (CTEs)
- Subqueries and correlated subqueries
- String, date, and NULL handling
- Excel functions, Pivot Tables, and charts
- Interview preparation patterns

## Contributing

Found an error or want to add more questions? Feel free to open an issue or submit a pull request.

## License

This project is open source and available for anyone to learn from and contribute to.
