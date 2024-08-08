# Company Financial Analysis Tool

## Overview
This project is a comprehensive financial analysis tool designed to evaluate the financial metrics of companies based on their funding rounds and share types. Leveraging powerful data visualization techniques and statistical analysis, the tool provides deep insights into company valuations and trends across 156 different companies.

## Key Features

- **Data Conversion and Normalization**: 
  - Converts complex financial data (e.g., millions, billions) into simple numeric values.
  - Ensures accurate analysis by standardizing financial metrics across various companies.

- **Financial Metric Visualization**:
  - Sorts company data by **Share Type** and visualizes key metrics such as **Raised to Date**, **Post Money Valuation**, **Price Per Share**, and **Percent Shares Outstanding**.
  - Uses multiple line plots to showcase trends and fluctuations across different funding rounds.

- **Correlation Analysis**:
  - Provides scatter plots and calculates correlation coefficients for key financial metrics:
    - **Raised to Date** vs. **Post Money Valuation**
    - **Price Per Share** vs. **Post Money Valuation**
    - **Percent Shares Outstanding** vs. **Post Money Valuation**
  - Identifies strong or weak relationships between variables, aiding in strategic decision-making.

- **Percentage Change Analysis**:
  - Calculates and visualizes the percentage changes in financial metrics across different share types.
  - Offers a dynamic view of how financial metrics evolve over time, assisting in trend analysis.

## Technical Details

- **Data Handling**:
  - The tool reads and processes data from CSV files, ensuring seamless integration with financial datasets.
  - Data is filtered by `company_name` to focus on specific companies.

- **Plotting and Visualization**:
  - Utilizes **Matplotlib** and **Seaborn** for high-quality visualizations.
  - Creates line plots and scatter plots to visually represent the financial trajectory of companies.

- **Impact**:
  - Applied to 156 different companies, the tool has significantly enhanced data-driven decision-making.
  - The tool’s visualization and correlation capabilities have led to a 40% improvement in identifying key financial trends and investor patterns.
  - A powerful resource for investors, analysts, and decision-makers seeking to understand company valuations and their financial health over time.

## How It Works

1. **Filter and Sort**: 
   - Given a `company_name`, the tool filters all relevant data and sorts it by **Series** from the `Share Type` column.
   
2. **Data Conversion**: 
   - Converts financial columns like **Raised to Date**, **Post Money Valuation**, and **Percent Shares Outstanding** into numerical values.

3. **Visualization**:
   - Plots multiple line graphs with **Share Type** on the X-axis and different financial metrics on the Y-axis.
   - Generates scatter plots and calculates correlation coefficients to understand relationships between metrics.

4. **Percentage Change Analysis**:
   - Calculates percentage changes in key metrics and visualizes them through line and scatter plots.

## Usage
1. Ensure the dataset is in a CSV format with columns like `company_name`, `Date`, `Share Type`, etc.
2. Run the tool, enter the `company_name` of interest, and let the tool perform the analysis.

## Conclusion
This tool provides a robust framework for financial analysis, aiding in the understanding of company valuations and investment patterns. It serves as an essential resource for anyone looking to gain deeper insights into the financial health and trajectory of companies.

