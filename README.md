# GlobalSalesReport
This repository contains the steps and analyses performed on the sales transaction data for a global retail store. The dataset includes information on orders, returns, and personnel across various regions and markets. The goal is to provide stakeholders with detailed insights and visualizations to enhance their understanding of order's return trends.

## Data Cleaning Steps
1. **Removed Column**: Removed the `Postal Code` column due to mostly blank data.
2. **Remove Duplicates**: Applied deduplication to ensure no duplicate entries.
3. **Remove Blank Rows**: Eliminated any blank rows in the dataset.
4. **Cross-Check Data Types**: Verified and corrected data types for consistency.
5. **No Missing Values**: Confirmed there were no missing values in the dataset.
6. **Order ID Deduplication**: Ensured uniqueness of `Order ID` in the `Orders` sheet.

## Model View
- **Star Schema**: Created connections using a star schema model for both fact and dimension tables to optimize the data structure.

## Report View
- **Visualizations**:
  - **Total Count & Total Return Count Cards**: Displayed the total number of orders and total returned orders.
  - **Clustered Column Chart**: Visualized returned orders based on category.
  - **Pie Chart**: Represented returned orders by market area.
  - **Map**: Illustrated returned orders by market area geographically.

## Contents
- **Orders Data**: Detailed records of sales transactions.
- **People Data**: Information about personnel and their regions.
- **Returns Data**: Records of returned orders categorized by market.
- **Data Cleaning Scripts**: Power Query scripts used for data cleaning and preprocessing.
- **Analysis Reports**: Power BI reports offering detailed insights and visualizations.

## Usage
1. Load the provided datasets into Power BI.
2. Utilize the data cleaning scripts in Power Query to prepare the data.
3. Explore the Power BI reports for comprehensive insights and recommendations.

