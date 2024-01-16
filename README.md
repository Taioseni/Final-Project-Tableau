What# Final-Project-Tableau

## Project/Goals
The goal of this project is to analyze and visualize the Airbnb dataset for New York City using Tableau. The objectives include understanding the distribution of room types, exploring the relationship between the number of beds and price, and examining the spatial and temporal aspects of Airbnb listings.


## Process
step 1: Connect my data: Loaded the dataset from "airbnb.xlsx" using Tableau.

step 2: Detect different data types: Used Tableau's data profiling features to identify data types and missing values. Converted relevant columns, such as 'Host Since,' to appropriate data types.

Step 3: Analysed five assessment in the data set such as [price distribution by neighbourhood, room type popularity and average price, trends in new prices over time, correlation between  number of beds and price and review scores vs price]

Step 4: Created a geographical map summary using the major features of the data set.

Step 5: Further analysed four questions based on data set and assessments from step 3 to understand the seasonality trends, neighbourhood pricing and ranges as well as the correlation between review scores and number of reviews with major focus on room types.

Step 6: Created a dashboard and linked each worksheets to one another for easier visualization. 

## Results
I chose Option 2, utilizing Tableau for the analysis.

1. Which neighbourhoods have the highest and lowest average prices?

The visualization type used is Bar chart - To see how different room types affect average prices in neighbourhoods and analyze how this impacts pricing in different areas.

This displayed the neighbourhood with the highest average price is Manhattan resulting with the total amount of 450.1 and the lowest is Bronx with a total amount of 291.1

2. Is there a seasonality in the Airbnb prices in New York City?

The visualization type used is Line graph - To compare different years and see how seasonality trends evolve and explore if seasonality effects vary by location.

The seasonality in the Airbnb prices in New York City was Manhattan which rose from 2008 to 2014 from 0 to 896,314 and declined in 2015 to 493,292 while staten remained the lowest from 2008 to 2015 at 1.928

Brooklyn increase in 2008 from 1,276 to 313,831 in 2012 and declined in 2013 (292,338) increased in 2014 to 344,612 and finally declined in 2015 to 197,677

Queens 2008(473) and rose to 79,915 in 2014 but declined to 49,604 in 2015

Bronx in 2009 started at 84 and rose to 7,310 in 2015

Staten started in 2009 at 139 rose to 10,145 in 2012 and declined to 1,928 in 2015

3. What is the average number of reviews per room type in different neighbourhoods? 

The visualization type used is stacked bar chart - To understand how the popularity or guest engagement, as indicated by the number of reviews, varies for different room types across various neighbourhoods.

The average number of reviews per room in different neighbourhoods are
Bronx: EH (7.54), PR (11.28), SR (4.74)
Brooklyn:  EH (12.42), PR (11.02), SR (6.27)
Manhattan:  EH (12.13), PR (13.38), SR (10.68)
Queens: EH (9.97), PR (11.96), SR (8.53)
Staten Island: EH (10.98), PR (15.68)

4. How do review scores correlate with the number of reviews?

The visualization type used is scatter plot - To analyze if the pattern varies across different areas and understand how room types might influence this relationship.

From the analysis, private rooms and entire homes had the highest number of reviews resulting in a high review score ratings. This could possibly mean that customers were highly satisfied with the services provided by the host. The total data per neighbourhood  for the entire homes and private room are as follows; 

Bronx: EH NOR (694) RSR (5,134), PR NOR (2,550) RSR (13,472),
Brooklyn: EH NOR (70,746) RSR (413,360), PR NOR (63,082) RSR (355,515)
Manhattan: EH NOR (124,537) RSR (708,269), PR NOR (71,317) RSR (346,041)
Queens: EH NOR (9,045) RSR (61,374), PR NOR (14,933) RSR (77,109) 
Staten Island: EH NOR (692) RSR (3,616), PR NOR (1,270) RSR (5,105)


## Challenges 
Cleaning and handling missing data in the dataset: removing affected entries using advanced techniques

Addressing outliers that might impact the accuracy of visualizations: Outliers management

Integrating external geographical data for precise mapping: Geospatial integration

Discrepancies in zip code leading to location error on the map and possibly inaccuracy in the dataset analysis.

Generated geographical coordinates (longitude and latitude) was mislaid in Africa. (Resolution – changed tableau location)


## Future Goals
If I had more time, I would:

Conduct more in-depth analysis, possibly incorporating machine learning models for price prediction.

Enhance the dashboard with additional interactive features for user engagement.

Explore external datasets to supplement insights, such as neighbourhood demographics or local events.
