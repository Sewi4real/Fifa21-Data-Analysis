# FIFA 21 Player Data Cleaning and Visualization

This project involves cleaning and visualizing the FIFA 21 player dataset. The dataset contains detailed information on footballers, including personal stats, club details, and contract values.

## Features

- Data cleaning (handling missing values, transforming units, parsing currencies)
- Exploratory data analysis (EDA)
- Visualizations of player distributions and club summaries

## Dataset

The raw dataset is named `fifa21_raw_data.csv`.

## Steps

1. **Gather**: Load and inspect the data.
2. **Assess**: Check for missing values, data types, duplicates.
3. **Clean**:
   - Convert height and weight to numerical formats
   - Normalize currencies (Value, Wage, Release Clause)
   - Fill missing values
   - Drop duplicates
4. **Visualize**:
   - Player age distribution
   - Top clubs by player count
   - Average player rating by position

## Visualizations

- 📊 Distribution of Player Ages
- 🏆 Top 10 Clubs by Player Count
- ⚽ Average Player Rating by Position

## How to Run

- Ensure you have the required Python libraries installed.
- Place `fifa21_raw_data.csv` in the root directory.
- Run the script `fifa21_analysis.py` or execute cells in the notebook (if using Jupyter).

## Author

Sewhenu Avoseh
