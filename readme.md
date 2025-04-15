# Top 2000 Global Companies Financial Data Analysis(Excel)

This dataset contains financial information on the top 2000 global companies in 2024. It includes key metrics such as company name, country, sales, profit, assets, and market value. The data offers valuable insights into the financial performance and market presence of leading companies across various industries worldwide. It is ideal for financial analysis, visualization, and global market research.

## Dataset Overview
- Rows: 2002
- Columns: 7

### Column Description
- Name: The name of the company.
- Country: The country where the company is based.
- Sales: Total sales revenue of the company.
- Profit: Net profit of the company.
- Assets: Total assets held by the company.
- Market Value: The market capitalization of the company.

## Questions

### Data Cleaning And Preprocessing
- Convert Text To Numbers: The Sales, Profit, Assets, and Market Value columns contain financial values with $ and B. Write a formula or use Power Query to convert them into numeric values.
- Handle Missing Data: Identify and highlight missing or inconsistent values in the dataset. Use Excel functions like IFERROR, IFNA, and ISBLANK to handle them appropriately.

### Data Analysis And Calculations
- Top Performing Companies: Using formulas, identify the top 10 companies with the highest profit.
- Market Share Calculation: Calculate the market share of each company by dividing its market value by the total market value of all companies.
- Asset To Sales Ratio: Compute the asset-to-sales ratio for each company and categorize companies as:
High Ratio (Ratio > 10)
Medium Ratio (5 < Ratio < 10)
Low Ratio (Ratio < 5)
- Profitability Analysis: Find companies with a Profit Margin above 20%. (Profit Margin = (Profit / Sales) * 100).
- Conditional Formatting For Profit Growth: Highlight companies with a Profit greater than $50B using conditional formatting.
Advanced Excel Concepts
- Dynamic Data Extraction: Create a dropdown filter that allows users to select a country and dynamically display the top 10 companies from that country.
- Lookup And Match Functions: Implement a VLOOKUP or INDEX MATCH function to retrieve financial details of a company when its name is entered in a search cell.
- Company Segmentation: Use pivot tables to classify companies into different tiers based on Market Value:
Tier 1: Market Value > $500B
Tier 2: $100B < Market Value < $500B
Tier 3: Market Value < $100B

### Visualization And Dashboard
- Create an Interactive Dashboard: Build an Excel dashboard that includes:
A Bar Chart comparing Sales, Profit, and Assets for the top 10 companies.
A Pie Chart showing the distribution of companies by country.
A Line Chart visualizing total market value trends across different countries.
Interactive slicers for filtering by country and company size.
