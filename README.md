# Traffic Accident Data Analysis

This project analyzes traffic accident data to uncover patterns and trends related to road conditions, weather, and time of day. The insights gained from this analysis aim to develop targeted strategies to improve road safety and provide raod.

## Data Source

The dataset used in this project is the US Accidents dataset, which can be found [here](https://www.kaggle.com/sobhanmoosavi/us-accidents).

## Code Analysis

The analysis is performed using Python and involves the following steps:

1. **Data Loading and Initial Exploration**
    - Load the dataset using pandas
    - Display the first 10 rows of the dataset
    - Check the number of columns and rows
    - Display the columns of the dataset

2. **Data Cleaning and Preprocessing**
    - Check for missing and null values
    - Drop rows with missing values in crucial columns
    - Fill missing values in other columns with appropriate values
    - Convert date-time columns to the correct format

3. **Exploratory Data Analysis (EDA)**
    - Plot the percentage of missing data per column
    - Analyze the number of accidents in each city
    - Visualize the distribution of accidents by hour of the day, day of the week, and month of the year
    - Examine the distribution of accidents by severity and state
    - Plot the latitudes and longitudes of accidents

4. **Inferences and Visualizations**
    - Analyze the impact of weather conditions, visibility, and temperature on accident severity
    - Create various plots to visualize the findings

## Key Findings

- Cities with the highest number of accidents
- Time periods with the highest accident frequency
- States with the highest accident severity
- Weather conditions that contribute to higher accident rates

## Requirements

- pandas
- seaborn
- matplotlib

## Usage

To run the analysis, follow these steps:

1. Clone the repository
2. Install the required packages using `pip install pandas seaborn matplotlib`
3. Run the analysis script

```python
python traffic_accident_analysis.py
