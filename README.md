# PyBer_Analysis

# PyBer_Analysis

## Project Overview
The purpose of this assignment is to practice using matplotlib to visualize data and pandas to create series and dataframes in Jupyter Notebook by fullfilling V.Iualize's request to create:

- A DataFrame that summarizes the key metrics for the ride-sharing data by city type.
- A multiple-line chart, with on eline for each city type, that shows the sum of the fares for each week

## Resources
- Data Source:
    - city_data.csv
    - ride_data.csv
- Software: Jupyter Notebook, Python 3.8.2

## Steps
To create the summarize dataframe of the ride-share data, first import necessary dependencies, load the city_data.csv and ride_data.csv, create dataframes for each file and a combine the two DataFrames into one.
![Dependencies](https://github.com/sdang101/PyBer_Analysis/blob/master/analysis/Dependencies.png)

![Combined_Dataframe](https://github.com/sdang101/PyBer_Analysis/blob/master/analysis/Combined_Dataframe.png)

Use the merged DataFrame to get total rides, total drivers, and total fares for each city type.
![Totals](https://github.com/sdang101/PyBer_Analysis/blob/master/analysis/Totals.png)

Use the above DataFrames to find the average fare per ride and the average fare per driver.
![Average](https://github.com/sdang101/PyBer_Analysis/blob/master/analysis/Average.png)

Create summarized dataframe of the totals and average dataframes above. 
![Summarize DataFrame](https://github.com/sdang101/PyBer_Analysis/blob/master/analysis/Summarize%20DataFrame.png)
 
![PyBer_Summary_Df](https://github.com/sdang101/PyBer_Analysis/blob/master/analysis/PyBer_Summary_Df.png)
Looking at the summarized DataFrame total rides and total driver:
- Urban cities has the most rides (1,625) and drivers (2,405).
- Suburban cities has the second most rides (625) and drivers (490).
- Rural cities has the least amount of riders (125) and drivers (78).
Looking at the summarized DataFram total fares:
- Urban cities has the highest total fares ($39,854.38).
- Suburban cities has the second highest total fares ($19,356.33).
- Rural cities has the lowest total fares ($4,327.93).
Looking at average fare per ride and average fare per driver:
- Rural cities has the highest average fare per ride ($34.62) and drivers ($55.49).
- Suburban cities has the second highest average fare per ride ($30.97) and drivers ($39.50).
_ Urban cities has the lowest average fare per ride ($24.53) and drivers ($16.57)


![Challenge_Fig](https://github.com/sdang101/PyBer_Analysis/blob/master/analysis/Challenge_Fig.png)
