# Tennessee Major Cities Unemployment Analysis

## Overview

This project analyzes the unemployment data for major cities in Tennessee using data from the U.S. Bureau of Labor Statistics (BLS). The project fetches unemployment rates for 2023 and 2024 and visualizes the trends using heatmaps and bar charts to show the percentage change in average unemployment.

## Code

- `labor_analysis.ipynb`: Contains the Python code for fetching data from the BLS API, performing data analysis, and generating visualizations.

## Data Source

- U.S. Bureau of Labor Statistics (BLS) API

## Visualizations

- `2023_unemployment_heatmap.png`  ![Screenshot 2025-05-09 224036](https://github.com/user-attachments/assets/a26b02c6-ce18-4fb0-9b29-ac0a0e68fb06)
 - Heatmap showing the monthly unemployment rates for major Tennessee cities in 2023.
- `2024_unemployment_heatmap.png`  ![Screenshot 2025-05-09 224008](https://github.com/user-attachments/assets/5ced4750-267a-4159-9e73-e15c6c65c93b)
  - Heatmap showing the monthly unemployment rates for major Tennessee cities in 2024.
- `unemployment_change_bar_chart.png` ![Screenshot 2025-05-09 223928](https://github.com/user-attachments/assets/86b8c0eb-b7b2-4e93-9404-87561f326a98)
  - Bar chart illustrating the percentage change in the average unemployment rate from 2023 to 2024 for each city.

## Setup 
  Install the required Python libraries:
    ```bash
    pip install requests pandas seaborn matplotlib
    ```
  Obtain a BLS API registration key 


## Key Findings

- Memphis and Nashville showed the most significant increases in average unemployment from 2023 to 2024.
- Jackson was the only city in the analysis to experience a decrease in average unemployment.
- Other major cities showed relatively stable trends.



## License
