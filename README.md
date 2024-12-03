# project-1
## Amazon E-Commerce Sales Data Analysis
This analysis focuses on B2C Amazon sales from an e-commerce clothing store in India during the second quarter. 

Python was used to look into the overall performance throughout the quarter, and further find what factors affected order status (successfully delivered, cancelled, or returned) and total sales.

## Files
**Project 1 -Amazon E-Commerce Sales.pdf:** slides explaining sales analysis along with visualizations.

**Data:** has full sales data files.

**Cleaning data workbooks:**
- **cleaning.ipynb:** cleans main data file including dropping unrelated or unnecessary values, recategorizing columns, and adding new data columns.
- **cleaning_sales.ipynb:** recategorizes product information data including color and combines it with sales data.

**Cleaned data files:** (found under output)
- **cleaned_Amazon Sale Report.csv:** result from cleaning.ipynb
- **cleaned_Product Sales Info.csv:** output from cleaning_sales.ipynb

Analysis workbooks can be found in folders ending in _Work and include:
- time_analysis.ipynb: analyzes order sales throughout the quarter and factors in promotion.
- geography.ipynb: visually analyses order sales throughout the country with maps.

## Data Source
Data sourced from thedevastator on Kaggle: https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data?select=Amazon+Sale+Report.csv
