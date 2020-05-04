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
![0](https://github.com/sdang101/PyBer_Analysis/blob/master/analysis/0.png)
![1](https://github.com/sdang101/PyBer_Analysis/blob/master/analysis/1.png)
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

![2](https://github.com/sdang101/PyBer_Analysis/blob/master/analysis/2.png)
![3](https://github.com/sdang101/PyBer_Analysis/blob/master/analysis/3.png)
![4](https://github.com/sdang101/PyBer_Analysis/blob/master/analysis/4.png)
![5](https://github.com/sdang101/PyBer_Analysis/blob/master/analysis/5.png)

![Challenge_Fig](https://github.com/sdang101/PyBer_Analysis/blob/master/analysis/Challenge_Fig.png)

Looking at the multipleline plot, it shows the total fare by city type from 01/01/2019 to 04/28/2019. - Urban comes out on top consistently with peaks in at the beginnig and end of March and 
- Suburban comes out with the second most fares with a peak at the end of Feburary and a low point in April
- Rurual comes out with the lowest fares with a peak ath the end of February and in April.

## Challenges
Some challenges I encountered was downloading the ride_data.csv file. The ride_id colunm came out in sciencefic notation without the percise ride_ids. I had to keep downloading the file until I was given the percise ride_ids. I then checked it in Jupyter Notebook to see that the "correct" ride_data.csv was read.

## Farther Steps
It seems that cities with the most drivers and riders have the lowest average fare and highest total fares. To address this disparity, the CEO can decrease supply of drivers to increase the average fare in urban cities or giving a promotion in suburban and rural cities by giving those areas free first ride to the riders.

To gain more insight, it would be useful to get data on how far each rider is going for each city type along with how much that fare is, what time of day (morning, afternoon, evening, night) each rider is getting a ride share along with how much that fare costs. Maybe this will explain behaviors of the different type of cities of when riders order a ride and whether the cost fluctates depending on the time of say and how far/ how much each rider travels in the different city types

To perform this analyses, I use a scatterplot to plot the distance each rider travels for each type of city against how much those fare for each city type. I will also use another scatterplot to plot the time of day a rider rides in each city type verses the total fare for each city type.
