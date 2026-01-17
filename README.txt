Analyzing GDP deflator trends in Tunisia from 1970 to present.

## Overview
This project examines how Tunisia's price levels have changed over decades by analyzing official GDP deflator data. The GDP deflator is a key economic indicator showing overall price changes in an economy, providing insights into inflation and economic stability.

## What I Did
1. **Data Loading**: Imported raw Tunisian economic data from CSV files
2. **Data Cleaning**: 
   - Removed header rows with metadata
   - Converted data types (Year to integer, Value to numeric)
   - Handled missing values
3. **Analysis**:
   - Filtered specifically for GDP Deflator data
   - Calculated year-over-year percentage changes
   - Generated descriptive statistics
4. **Visualization**: Created time-series plots showing deflator trends over 50+ years
## Technologies Used
- Python 3.x
- pandas (data manipulation)
- matplotlib (visualization)
- Jupyter Notebook

## How to Run
1. Clone this repository
2. Install requirements: `pip install pandas matplotlib jupyter`
3. Open and run `Tunisia GDP Deflator.ipynb` in Jupyter

## Files
- `Tunisia GDP Deflator.ipynb` - Main analysis notebook
- `deflators_tun.csv` - Source data file

## Next Steps
Potential expansions:
- Compare with other economic indicators
- Add forecasting models
- Create interactive visualizations

## About the Data
Source: [Mention if you know the source - e.g., Tunisian government, World Bank, etc.]
Period: 1970-2024

Indicators: GDP Deflator values
