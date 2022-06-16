# PyBer_Analysis
## Purpose
-  purpose of our analysis is to create a summary dataframe that will show ride sharing data by city type(Rural,Urban & Suburban). Once we find our data we are going to create a multiple line graph that shows total weekly fares by each city type. How we first pulled our data is by using the pandas Groupby() function with the count() and sum () to get the total number of drivers,rides and fares by city type. Once we pulled this information and assigned it to functions we were able to calculate our average fare per ride and driver. Once we had all of that information together we were able to format into a newdata frame and re-format the columns. In the second part of this excercise we used the pivot() and resample function to create a multiple line graph that shows the total fares for each week by city type between the months of January & April of 2019.

## Overview
- Deliverable 1: A ride-sharing summary DataFrame by city type
- Deliverable 2: A multiple-line chart of total fares for each city type
- Deliverable 3: A written report for the PyBer analysis [README.md]

## Deliverable 1: A Ride-Sharing Summary DataFrame by City Type

### Tasks: 
- The total number of rides for each city type is retrieved.
- The total number of drivers for each city type is retrieved.
- The sum of the fares for each city type is retrieved.
- The average fare per ride for each city type is calculated.
- The average fare per driver for each city type is calculated.
- A PyBer summary DataFrame is created.
- The PyBer summary DataFrame is formatted as shown in the example.

### Results: 

## Deliverable 2: A multiple-line chart of total fares for each City type

### Tasks: 
- A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time.
- A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare."
- A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-29.
- A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week.
- An annotated chart showing the total fares by city type is created and saved to the "analysis" folder.

### Results: 



# Deliverable 3: A written report for the PyBer Analysis

### Overview of analaysis 
Rural cities has the least amount of drivers, rides and total fares.
Urban cities have the most amount of drivers, rides and total fares.
Suburban cities are in the middle having the 2nd most drivers, rides and total fares.
Although Rural cities see the least amount of drivers,rides & fares the have the highest average of fare per ride and fare per driver.
Although the Urban cities command the most drivers, rides and fares they have the lowest average of fare per ride and fare per driver.

### Summary 
Opportunities to expand the business in rural and suburban cities, including hiring drivers

The Urban cities - opportunities to expand rides.

The Rural cities - opportunity to expand fares Total Fare by City Type






