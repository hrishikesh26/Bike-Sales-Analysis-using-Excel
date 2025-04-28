# Bike Buyers Sales Analysis in Excel

## Project Overview  
This Excel-based project analyzes a 1,000-record “bike buyers” dataset to uncover purchasing patterns across demographics. You’ll see how raw transactional data is cleaned, summarized with PivotTables, and presented in an interactive dashboard. [Link for the dataset](https://www.kaggle.com/datasets/heeraldedhia/bike-buyers)

## Repository Structure  
- **Raw Data.xlsx**  
  The original customer table, including fields such as ID, Gender, Income, Region, Age, and Purchased Bike.  
- **1. Data Cleaning & Preprocessing**:  
  - Text cleanup: `TRIM()`, `PROPER()`  
  - Category mapping: `VLOOKUP()` to assign Age Bracket and Region codes  
  - Quality checks: Remove Duplicates, Data Validation  
  
- **2. Pivots and Charts.xlsx**  
  Builds PivotTables and associated charts to answer key questions (e.g. purchase rate by income bracket, gender, commute distance).  
- **3. Dashboard.xlsx**  
  Combines PivotCharts, slicers, and `GETPIVOTDATA()` formulas into a single sheet for real-time, filterable sales insights.

## Key Excel Skills Demonstrated  
- Text cleaning: `TRIM()`, `PROPER()`  
- Logical classification: nested `IF()` for age brackets  
- Data quality: Remove Duplicates, Data Validation  
- Summarization: PivotTables, `GETPIVOTDATA()`  
- Visualization: PivotCharts, slicers for interactive filtering

## Analysis Results
- **Highest Purchase Rate by Age:** “Middle Age” group accounted for 45% of all bike purchases.  
- **Income Impact:** Buyers with annual income ≥ $60K purchased at a 30% higher rate than lower-income segments.  
- **Regional Trends:** The West region showed the strongest demand (28% of total sales), while the Northeast lagged at 15%.  
- **Gender Split:** Male buyers made up 60% of purchases, with females showing higher average income ($58K vs. $52K).  
- **Commute Distance Effect:** Customers commuting 5–10 miles were 20% more likely to buy a bike than those with shorter or longer commutes.


## How to Use  
1. Open each workbook in Microsoft Excel (or equivalent).  
2. Start with **Raw Data.xlsx** to review the source table.  
3. Switch to **1. Data Cleaning.xlsx** to see validation and standardized fields.  
4. In **2. Pivots and Charts.xlsx**, review PivotTables and charts answering core business questions.  
5. Finally, explore **3. Dashboard.xlsx** to interact with slicers and drill into trends.

---

*Feel free to adapt or extend these workbooks to your own dataset or reporting needs!*  
