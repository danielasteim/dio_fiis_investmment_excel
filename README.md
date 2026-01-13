# dio_fiis_investmment_excel

Perfeito. Segue uma versão **mais técnica, objetiva e adequada para GitHub**, sem linguagem promocional:

---

# FII Investment Simulator (Excel)

Excel-based spreadsheet designed to simulate long-term investments in Brazilian Real Estate Investment Funds (FIIs), focusing on monthly contributions, portfolio yield, and income generation.
The project aims to support financial planning through deterministic projections and structured allocation strategies based on investor profile.

## Features

### 1. Configuration Section

User-defined inputs:

* Monthly salary
* Expected real portfolio yield (%)
* Investment rate over income

Derived outputs:

* Monthly investment amount
* Suggested investment timing based on income capacity

### 2. Monthly Investment Simulation Table

Core projection table containing:

* Monthly contribution value
* Investment horizon (years)
* Accumulated portfolio value
* Estimated monthly dividends

Calculations assume constant contribution and yield over time.

### 3. Scenario Analysis Table

Comparative projection of portfolio value and monthly dividends for fixed horizons:

* 1 year
* 2 years
* 5 years
* 10 years
* 20 years

Used for quick evaluation of long-term outcomes.

### 4. Investor Profile Allocation Table
Based on a selected investor profile (e.g. conservative, moderate, aggressive), the spreadsheet outputs:
* Allocation percentage per FII category
* Recommended investment amount per category
Logic is implemented using auxiliary lookup tables.

## Technical Implementation

* Excel formulas and financial calculations
* Auxiliary tables for parameterization
* `VLOOKUP (PROCV)` for dynamic allocation and recommendations
* Structured formatting for readability and usability

## Learning Outcomes

* Advanced Excel modeling for financial simulations
* Practical application of lookup tables and conditional logic
* Deeper understanding of FII mechanics and income-based portfolios

## Purpose
Provide a structured and transparent Excel model to simulate FII investments and support data-driven financial decisions.

