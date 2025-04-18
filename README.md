# Analyzing Wildfire Activities in Australia (Data Visualization)

## Introduction

This project involves the analysis and visualization of historical wildfire data in Australia. The dataset used contains information on various aspects of wildfires, including the region, date, estimated fire area, mean estimated fire brightness, and more.

## Project Overview

The analysis includes visualizations of different aspects of wildfire data, exploring trends over time, distribution across regions, and relationships between various parameters.

## Technologies Used

- Python
- Libraries: NumPy, Pandas, Matplotlib, Seaborn, Folium

## Dataset

The dataset is sourced from the following URL:
[Historical Wildfires Dataset](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/Historical_Wildfires.csv)

## Data Preprocessing

1. Loading the dataset.
2. Extracting additional features such as year and month from the 'Date' column.
3. Converting data types to appropriate formats.

## Data Visualizations

### 1. Change in Average Estimated Fire Area Over Time

Visualizing the change in the average estimated fire area over the years.

### 2. Estimated Fire Area for Each Year Grouped by Month

Examining the variation in estimated fire area for each year, grouped by month.

### 3. Distribution of Mean Estimated Fire Brightness Across Regions

Bar chart displaying the distribution of mean estimated fire brightness across different regions.

### 4. Portion of Count of Pixels for Presumed Vegetation Fires Across Regions

Pie chart illustrating the percentage of pixels for presumed vegetation fires in each region.

### 5. Histogram of Mean Estimated Fire Brightness

Histogram depicting the distribution of mean estimated fire brightness.

### 6. Distribution of Estimated Fire Brightness Across Regions

Stacked histogram showing the distribution of estimated fire brightness across regions.

### 7. Correlation Between Mean Estimated Fire Radiative Power and Mean Confidence Level

Scatter plot examining the correlation between mean estimated fire radiative power and mean confidence level.

### 8. Mapping Wildfire Regions in Australia

Marking the seven regions (NSW, QL, SA, TA, VI, WA, NT) on the map of Australia using Folium.

## Conclusion

This project provides a comprehensive analysis and visualization of wildfire activities in Australia, offering insights into trends, regional variations, and correlations between different parameters. The visualizations aid in better understanding the patterns and dynamics of wildfires over the years.

# Visualization Note

## **Map Display Limitation:**
Due to notebook constraints, the map showing marked wildfire regions in Australia is not visible in the notebook. Refer to the attached image below for a visual representation.

![aus_map_image](https://github.com/JayshreeMishra/analyzing_wildfire_activities_in_australia/blob/main/Aus_fire_map.jpeg)
