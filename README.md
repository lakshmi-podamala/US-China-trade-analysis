

# U.S.-China Trade Analysis (2017–2025)
## Project Overview

This project analyzes trade data between the United States and China from 2017 to 2025. The dataset contains monthly import and export values between the two countries, and this project calculates the total imports, exports, and trade balance. The goal is to visualize trends, track the trade balance over the years, and analyze year-over-year changes in imports and exports.

## Data Overview

The dataset used in this project includes the following key columns:
- `year`: The year of the trade data.
- `CTYNAME`: The country name (in this case, "China").
- `IJAN`, `IFEB`, ..., `IDEC`: Monthly import values for each year (January to December).
- `EJAN`, `EFEB`, ..., `EDEC`: Monthly export values for each year (January to December).
-  IYR, EYR
### Data Cleaning and Filtering:
- The data was filtered to include only records from the years 2017 to 2025.
- Missing values were handled by filling NaN values with zeros in the monthly import/export columns.
- The analysis was focused on trade with China.

## Features and Functionality

### Data Preparation:
- **Imports and Exports**: The total imports and exports were calculated by summing the monthly import and export values for each year.
- **Trade Balance**: The trade balance is computed by subtracting total imports from total exports.

### Key Analysis:
- **Time Series Visualization**: Plots were generated to visualize the U.S.'s trade with China over the years, showing trends in imports and exports.
- **Trade Balance Visualization**: A bar chart was used to show the U.S. trade balance with China for each year.
- **Year-over-Year Change**: The year-over-year percentage change in both imports and exports was calculated and visualized.

### Insights:
- The project helps in understanding how trade between the U.S. and China has evolved over time, including changes in trade volumes and trade balance.
- The year-over-year analysis shows fluctuations in trade growth rates, providing insights into key economic events.

## Dependencies

The following Python libraries are required to run this project:
- `pandas` for data manipulation.
- `numpy` for numerical operations.
- `matplotlib` for data visualization.

 ## Download links
 
https://github.com/lakshmi-podamala/US-China-trade-analysis/blob/main/Python.xlsx
https://github.com/lakshmi-podamala/US-China-trade-analysis/blob/main/Python_filtered.xlsx
- 
