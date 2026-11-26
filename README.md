# Database Design & SQL Development

A practical academic portfolio project documenting database modelling, relational design, SQL development, and advanced SQL topics completed across **Databases Laboratory 1–4** at **HAW Hamburg**.

The work follows a database-development progression: translate requirements into conceptual models, convert those models into relational schemas, implement and query relational databases, and explore views and transaction behaviour.

> **Coursework note:** The exercises were completed as part of university laboratory work. Where an exercise was completed in a team, contributions and individual understanding should be described accurately. This repository is being organized as a learning portfolio; solutions, diagrams, and scripts will be added and documented as they are prepared for publication.

## Contents

| Lab | Focus | Main topics |
|---|---|---|
| [Lab 1 – Database Modelling](./Lab-01-Database-Modelling/) | Conceptual design | ER diagrams, Chen notation, MC notation, entities, relationships, cardinalities, keys, integrity requirements |
| [Lab 2 – Relational Design](./Lab-02-Relational-Design/) | Relational modelling and theory | ER-to-relational mapping, functional dependencies, candidate keys, 1NF/2NF/3NF, relational algebra |
| [Lab 3 – SQL Development](./Lab-03-SQL-Development/) | SQL implementation and querying | DDL, sample data, constraints, joins, filtering, aggregation, grouping, subqueries, SQL and relational algebra |
| [Lab 4 – Advanced SQL](./Lab-04-Advanced-SQL/) | Views and transaction behaviour | Transactions, COMMIT, ROLLBACK, views, WITH CHECK OPTION, two-session visibility |

## Learning objectives and skills

- **Conceptual database design:** identify entities, attributes, keys, relationships, cardinalities, and semantic integrity requirements; model requirements using Chen and MC notation.
- **Relational database design:** map ER models to relational schemas and identify primary keys, foreign keys, and relationship tables.
- **Relational theory:** determine functional dependencies and candidate keys; decompose relations and assess 1NF, 2NF, and 3NF.
- **SQL implementation:** create tables, choose data types, define constraints, and insert, update, and delete data.
- **SQL querying:** retrieve and combine data using joins, predicates, subqueries, ordering, aggregate functions, GROUP BY, and HAVING.
- **Database views:** create views over one or more tables and examine which view modifications are supported, including the effect of WITH CHECK OPTION.
- **Transaction management:** use multi-statement transactions, COMMIT, and ROLLBACK; observe the visibility of uncommitted and committed changes from separate database sessions.
- **Relational algebra:** express query requirements in relational algebra and translate them into SQL.

## Repository structure

```text
database-design-and-sql-development/
├── README.md
├── Lab-01-Database-Modelling/
│   ├── README.md
│   ├── ER-Diagrams/
│   └── relational-models/
├── Lab-02-Relational-Design/
│   ├── README.md
│   ├── schemas/
│   ├── normalization/
│   └── relational-algebra/
├── Lab-03-SQL-Development/
│   ├── README.md
│   ├── student-information-system/
│   ├── shipping-company/
│   ├── company-database/
│   ├── cinema-database/
│   └── weather-database/
└── Lab-04-Advanced-SQL/
    ├── README.md
    ├── chemistry-database/
    ├── geography-database/
    ├── company-views/
    └── transaction-management/
```

## Lab overview

### Lab 1 – Database Modelling

The exercises include modelling a student information system, a movie database, a bar owner’s business, a zoo, a laboratory organization, and a cooking club. The tasks focus on identifying entity and relationship types, attributes and keys, representing relationship constraints, and considering semantic integrity requirements.

### Lab 2 – Relational Design

The exercises cover converting ER diagrams into relational schemas (including student, hotel, books, and laboratory scenarios), identifying functional dependencies and keys, normalizing relations into 2NF and 3NF, drawing an ERD from a normalized schema, and writing relational algebra expressions for query requirements.

### Lab 3 – SQL Development

The exercises include creating and populating a student information database, querying shipping-company data, working with the COMPANY example database, and expressing cinema and weather database queries in both relational algebra and SQL. Topics include table definitions, constraints, joins, aggregate queries, subqueries, and referential actions.

### Lab 4 – Advanced SQL

The exercises use chemistry, geography, and COMPANY databases. They cover transaction-based multi-table changes with change logging, creating and testing views, the WITH CHECK OPTION, and observing transaction visibility between two database sessions before and after COMMIT and ROLLBACK.

## How to explore or run the SQL

SQL files will be grouped by scenario within the relevant lab folder. When scripts are added, each scenario folder should explain:

1. The database or schema required.
2. The order in which scripts should be executed.
3. Any setup script or sample data needed.
4. Example queries and their expected purpose.
5. Any assumptions or database-specific syntax.

The SQL exercises use MySQL in the laboratory materials where a database platform is specified. Check each scenario's instructions before running scripts; some exercises rely on supplied course databases or setup scripts.

## Tools

- SQL
- MySQL / MySQL Workbench (for the exercises using MySQL)
- Entity-Relationship modelling
- Relational algebra

## Academic context

**Course:** Databases Laboratory 1–4  
**Institution:** HAW Hamburg  
**Project type:** Academic coursework / learning portfolio

This repository is intended to document the design decisions, implementation work, and database concepts practised in the laboratories. It is not presented as a production database application.

## Responsible publication

Before publishing coursework solutions, check the university's rules on sharing assignment material. Do not upload restricted course files, personal data, student identifiers, credentials, or database dumps containing sensitive information. Prefer original explanations, redrawn diagrams, and small synthetic datasets.

---

**Author:** [Minhazul22](https://github.com/Minhazul22)
