# Data Observation: Video Game Sales Analysis

## Overview
This Jupyter notebook provides an analysis of video game sales data across various platforms and regions. The dataset `vgsales.csv` includes information on game rankings, sales figures, release years, and publishers.

### Data Source
The dataset consists of 16,598 rows and 11 columns, detailing sales figures for video games globally and across regions like North America, Europe, and Japan.

### Libraries Used
- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations.

### Data Columns:
1. **Rank**: The rank of the game based on global sales.
2. **Name**: The name of the game.
3. **Platform**: The platform (e.g., Wii, NES) the game is released on.
4. **Year**: The release year of the game (some missing values).
5. **Genre**: The genre of the game (e.g., Sports, Racing).
6. **Publisher**: The publisher of the game (some missing values).
7. **NA_Sales**: Sales in North America (in millions).
8. **EU_Sales**: Sales in Europe (in millions).
9. **JP_Sales**: Sales in Japan (in millions).
10. **Other_Sales**: Sales in other regions (in millions).
11. **Global_Sales**: Total global sales (in millions).

### Actions Performed:
- The dataset is loaded into a pandas DataFrame (`df`).
- The structure of the dataset is inspected using `df.info()` to check for missing values and column types.

## Future Analysis
The dataset can be used for further analysis, such as:
- Identifying trends in global sales across platforms and regions.
- Analyzing the most successful genres or publishers.
- Visualizing sales distribution over the years.

## Requirements
- Python 3.x
- Jupyter Notebook
- pandas, numpy
