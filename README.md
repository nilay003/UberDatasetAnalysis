# UberDatasetAnalysis

This project analyzes Uber trip data using Python libraries like pandas, numpy, matplotlib, and seaborn. The analysis includes data cleansing, exploratory data analysis (EDA), and visualizations to gain insights into ride patterns, trip distances, and trip categories (Business vs. Personal).

## Project Overview

This project focuses on:
- Identifying unique starting and stopping destinations
- Analyzing miles traveled for different trip purposes
- Visualizing data related to trip categories (Business vs. Personal)

## Data

The dataset used for this project is `uberdrive.csv`, which contains the following key fields:

| Column         | Description                                          |
|----------------|------------------------------------------------------|
| `START_DATE*`  | The date when the trip started.                     |
| `END_DATE*`    | The date when the trip ended.                       |
| `CATEGORY*`    | The category of the trip (e.g., Business or Personal). |
| `START*`       | Starting location of the trip.                      |
| `STOP*`        | Stopping location of the trip.                      |
| `MILES*`       | Distance traveled during the trip (in miles).      |
| `PURPOSE*`     | Purpose of the trip (e.g., Meeting, Meal/Entertainment). |

## Key Features

- Data Cleansing:
  - Handle missing values by removing rows with null entries.
  - Inspect the dataset structure, size, and statistics.

- Exploratory Data Analysis (EDA):
  - Calculate the number of unique starting and stopping destinations.
  - Analyze the most frequent starting and stopping points.
  - Determine the total miles traveled for each trip purpose.

- Visualizations:
  - Bar plot showing miles traveled by purpose.
  - Visualize the distribution of trip categories (Business vs. Personal).

## Visualizations

- Miles Traveled by Purpose: ![Miles by Purpose]
![image](https://github.com/user-attachments/assets/9694dc5f-5929-481b-b892-e46267fae212)
![image](https://github.com/user-attachments/assets/31b0b60d-d073-40ef-8e89-72d5ade83b8b)

- Business vs. Personal Trips: ![Category Analysis]
- ![image](https://github.com/user-attachments/assets/d0348301-e015-4b55-9218-721615ef34ea)



## Conclusion

This analysis provides valuable insights into Uber trip patterns and helps better understand trip behaviors based on purpose and category.

## Future Enhancements

- Add time-series analysis to study trends over time.
- Implement geospatial analysis to map trips visually.
