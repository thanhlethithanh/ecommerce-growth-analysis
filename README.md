# Plato's Pizza: Revenues and Operations Analysis

[![SQL Server](https://img.shields.io/badge/SQL%20Server-Data%20Analysis-red?logo=microsoft-sql-server&logoColor=white)](https://www.microsoft.com/en-us/sql-server/)
[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=power-bi&logoColor=black)](https://powerbi.microsoft.com/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

## Project Overview

A comprehensive data analysis of Plato's Pizza, a Greek-inspired pizzeria in New Jersey, examining one full year of operations (21,350 orders, $817,860 revenue). **The analysis identifies operational inefficiencies that could increase revenue without significant capital investment.**

**Insights and recommendations are provided on the following key areas:**
- Revenue Growth (Total Sales & Trends)
- Market Demand (Order Frequency & Volume)
- Transaction Value (Average Spend per Customer)
- Product Performance (Quantity per Order)

# Data Structure & Initial Checks

### Data Schema Overview
The dataset consists of four interconnected tables containing 21,350 unique orders and over 49,000 line items:

| Table | Records | Attributes |
| :--- | :--- | :--- |
| **Orders** | 21,350 | Transaction ID, Date, Time |
| **Order Details** | 49,000+ | Line item mapping, Quantity per pizza |
| **Pizzas** | 32 | Pizza ID, Size, Unit Price |
| **Pizza Types** | 32 | Name, Category (Classic, Veggie, etc.), Ingredients |

**ERD**
<img width="520" height="267" alt="Pizza_ERD" src="https://github.com/user-attachments/assets/3f7f5a4d-a6dd-427a-903d-a3dbdb61269f" />


# Executive Summary

### Overview of Findings

Explain the overarching findings, trends, and themes in 2-3 sentences here. This section should address the question: "If a stakeholder were to take away 3 main insights from your project, what are the most important things they should know?" You can put yourself in the shoes of a specific stakeholder - for example, a marketing manager or finance director - to think creatively about this section.

[Visualization, including a graph of overall trends or snapshot of a dashboard]



# Insights Deep Dive
### Category 1:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 1]


### Category 2:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 2]


### Category 3:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 3]


### Category 4:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 4]



# Recommendations:

Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following: 

* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  


# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* Assumption 1 (ex: missing country records were for customers based in the US, and were re-coded to be US citizens)
  
* Assumption 1 (ex: data for December 2021 was missing - this was imputed using a combination of historical trends and December 2020 data)
  
* Assumption 1 (ex: because 3% of the refund date column contained non-sensical dates, these were excluded from the analysis)




