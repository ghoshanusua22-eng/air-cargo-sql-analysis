# air-cargo-sql-analysis
SQL-based analysis of the Air Cargo aviation dataset to optimize flight routes, analyze passenger trends, and calculate revenue insights.
# Air Cargo SQL Analysis | MySQL

## Project Overview
An end-to-end SQL analysis project on Air Cargo 
aviation dataset using MySQL Workbench covering 
50 customers, 49 routes across 4 interconnected 
tables with 16 advanced MySQL queries.

## Key Metrics Analysed
- Total Revenue: Rs.15,369 (53% above target)
- Business Class Revenue: Rs.6,034 (39% of total)
- Active Customers: 41 out of 50 registered
- Inactive Customers: 9 (win-back opportunity)
- Emirates Customers: 14 unique travelers
- Long-Haul Routes: 24 routes above 2000 miles
- Avg Passengers per Route: 1.5625

## SQL Techniques Used
- JOINs — INNER JOIN with DISTINCT
- Subqueries — nested queries with IN()
- Window Functions — MAX() OVER PARTITION BY
- ROLLUP — subtotals and grand totals
- Stored Procedures — reusable SQL logic
- Views — virtual tables for reporting
- Indexes — query performance optimization
- EXPLAIN — execution plan validation
- IF() — business logic inside SQL
- User Management — CREATE USER, GRANT

## Database Tables
| Table | Records | Role |
|---|---|---|
| customer | 50 | Master customer info |
| passengers_on_flights | 50 | Flight travel records |
| routes | 49 | Route master data |
| ticket_details | 50 | Ticket purchase details |

## Business Insights Derived
- Business class generates 39% of total revenue
  despite fewer passengers — key pricing insight
- 9 inactive customers identified for targeted
  win-back marketing campaigns
- 24 long-haul routes flagged for larger
  aircraft allocation
- Average 1.56 passengers per route shows
  underutilization — optimize aircraft size

## Tools Used
- MySQL Workbench
- MySQL 8.0
- CSV datasets (4 files)

## Certification
Data Acquisition and Manipulation using SQL
Simplilearn | April 2026 | Code: 10143314
MySQL, Joins, and Window Functions
https://drive.google.com/file/d/1t9F65o-_qUYkqL7Ap0NOdUwWHG5aJCdK/view?usp=sharing
## Link of the project - https://drive.google.com/file/d/1OUEGnpA0uuJD0RLLF7ReHjPGW0uqtj5i/view?usp=sharing
