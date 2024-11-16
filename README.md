# PhonePe_Case_Study_Python

# PhonePe Data Analysis Project

## Overview
This project involves a comprehensive analysis of PhonePe's transaction and user metrics from Q1 2018 to Q2 2021. The goal was to identify trends, patterns, and areas of improvement to provide actionable recommendations for enhancing app performance, user engagement, and market penetration.

## Data Sources
The analysis was conducted on a dataset containing:
- State-level and district-level transaction data, including transaction volumes, values, and types.
- Device-specific user registrations and demographic data.
- Population density and other regional statistics.

## Tools and Technologies
- **Python**: Data analysis and visualization.
- **Pandas**: Data manipulation and cleaning.
- **Matplotlib**: Visualization of trends and patterns.
- **Excel**: Data validation and initial inspection.

## Processes
1. **Data Loading**: Imported the raw data from the provided Excel file using `pandas`.  
2. **Data Inspection**: Previewed the data with `.head()`, checked for null values, and validated column names.  
3. **Data Cleaning**: Removed duplicates and handled missing values where applicable.  
4. **Feature Engineering**: Derived metrics like average transaction value (ATV) and total transactions by combining columns.  
5. **Descriptive Analysis**: Summarized transaction volumes, user counts, and transaction values using aggregate functions.  
6. **Trend Analysis**: Analyzed growth over time using quarter-wise and year-wise data groupings.  
7. **Category Analysis**: Segmented transaction data into types (e.g., peer-to-peer, merchant payments) and compared volumes and values.  
8. **Regional Analysis**: Compared user and transaction metrics across states and districts.  
9. **Device Analysis**: Analyzed user registrations by device brand to understand preferences.  
10. **Visualization**: Created bar charts, line plots, and pie charts to highlight trends and comparisons.  
11. **Insights Extraction**: Summarized findings based on analysis and visualizations.

## Key Insights
1. **Transaction Growth**: Consistent increase in transaction volumes and values across most states over the years.
2. **Popular Transaction Types**: Peer-to-peer payments dominate transaction volumes, followed by merchant payments and recharge/bill payments.
3. **Device Preferences**: Certain brands have a higher share of registered users, indicating device preferences among PhonePe users.
4. **Regional Engagement**: Strong adoption in urban areas, with specific districts outperforming others despite lower population density.
5. **Demographic Correlations**: Population density and transaction usage show a correlation, with urban regions leading in engagement.

## Recommendations
1. **App Optimization**: Focus on optimizing app performance for the most-used devices and introducing features tailored to them.
2. **Merchant Payments Growth**: Run targeted campaigns or cashback offers to increase the value of merchant transactions.
3. **Localized Marketing**: Deploy region-specific strategies to increase adoption in low-engagement areas.
4. **Rural Accessibility**: Enhance rural penetration through language localization and a simplified user interface.
5. **Personalized Features**: Introduce personalized recommendations for frequently used services based on transaction history.

## Project Structure
- **Raw Data**: `phonepe-pulse_raw-data_q12018-to-q22021.xlsx`
- **Jupyter Notebook**: `PhonePe_CaseStudy.ipynb` containing detailed analysis and visualizations.

## How to Use
1. Clone the repository:  
   ```bash
   git clone <https://github.com/RohitVelampudi/PhonePe_Case_Study_Python>
