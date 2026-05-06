# 🍕 Plato's Pizza: A Year in Review

[![SQL](https://img.shields.io/badge/SQL-PostgreSQL-blue)](https://www.postgresql.org/)
[![Tableau](https://img.shields.io/badge/Tableau-Dashboard-orange)](https://www.tableau.com/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

## 📊 Project Overview

A comprehensive data analysis of Plato's Pizza, a Greek-inspired pizzeria in New Jersey, examining one full year of operations (21,350 orders, $817,860 revenue). The analysis identifies operational inefficiencies that could increase revenue without significant capital investment.

**Key Business Metrics:**
- **Total Revenue:** $817,860
- **Total Orders:** 21,350
- **Average Order Value:** $38.31
- **Average Pizzas Per Order:** 2.3

## 🎯 Business Impact

This analysis uncovered **$150,000+ in annual profit opportunities** with minimal investment (<$2,000):

| Opportunity | Annual Impact | Investment | Payback |
|-------------|---------------|------------|---------|
| Seating reconfiguration | $40,000+ | $1,000 | 3 weeks |
| Menu simplification | $10,000+ (cost savings) | $0 | Immediate |
| Average order value increase | $106,750 | $0 (staff training) | Immediate |

## 📁 Database Structure

The database contains four tables with 21,350 orders and 49,000+ order detail records:

```sql
-- Table overview
orders          -- 21,350 rows | Order ID, date, time
order_details   -- 49,000+ rows | Line items, quantity
pizzas          -- 32 rows | Pizza ID, size, price
pizza_types     -- 32 rows | Name, category, ingredients
