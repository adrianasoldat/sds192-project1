# MTA Daily Ridership Analysis (2020–2025)

## Description
This project analyzes trends in New York City’s public transportation ridership before, during, and after the COVID-19 pandemic using the MTA Daily Ridership Data (2020–2025). The goal is to explore how ridership levels have changed over time and whether recovery patterns differ by transportation type (e.g., subway vs. bus) or by day of the week. The analysis uses daily ridership counts and usage ratios to identify long-term behavioral shifts in transit usage.

## Author
Adriana Soldat  
Smith College  
asoldat@smith.edu

## Repository Structure
- **data/**  
  Contains the dataset used for this project.  
  - `MTA_Ridership_Revised.csv`: Cleaned dataset with date, transport mode, total ridership, and usage ratio.

- **scripts/**  
  Includes R scripts used for data cleaning, feature engineering, and visualization.  
  - `data_cleaning.R`: Creates the revised dataset and exports it as a CSV file.  
  - `analysis.R`: Performs exploratory analysis and generates plots.

- **figures/**  
  Contains output graphs and visualizations (e.g., ridership trends, recovery comparisons).

- **README.md**  
  Provides a summary of the project, its purpose, author, and file structure.

## Notes
All data were obtained from the MTA’s publicly available ridership records. The revised dataset has been cleaned and formatted in long (tidy) structure, making it suitable for analysis and visualization.
