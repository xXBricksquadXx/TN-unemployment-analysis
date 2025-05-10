# Tennessee Major Cities Unemployment Analysis

## Overview

This project analyzes the unemployment data for major cities in Tennessee using data from the U.S. Bureau of Labor Statistics (BLS). The project fetches unemployment rates for 2023 and 2024 and visualizes the trends using heatmaps and bar charts to show the percentage change in average unemployment.

## Code

- `labor_analysis.ipynb`: Contains the Python code for fetching data from the BLS API, performing data analysis, and generating visualizations.

## Data Source

- U.S. Bureau of Labor Statistics (BLS) API

## Visualizations


- `2023_unemployment_heatmap.png` ![Screenshot 2025-05-09 125654](https://github.com/user-attachments/assets/b5bcc4ce-4acd-492d-8b21-37e1f6496f96) - Heatmap showing the monthly unemployment rates for major Tennessee cities in 2023.
- `2024_unemployment_heatmap.png` ![Screenshot 2025-05-09 125853](https://github.com/user-attachments/assets/28cf4c17-d712-462a-a8be-90635cc3f9c9)  - Heatmap showing the monthly unemployment rates for major Tennessee cities in 2024.
- `unemployment_change_bar_chart.png` ![Screenshot 2025-05-09 125514](https://github.com/user-attachments/assets/dc75e689-60d6-4707-9a48-b6d082e6d273) - Bar chart illustrating the percentage change in the average unemployment rate from 2023 to 2024 for each city.

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
