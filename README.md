# Surfs Up Analysis
## Overview of Project
### Purpose
The purpose of this project is to acquire more information about temperature trends in Hawaii before a new surf shop is opened there. This project gathers the temperature data of Oahu for the months of June and December. This information will help determine if a surf and ice cream shop business is sustainable year-round. The weather data for this project was stored in a SQLite database. The analysis was done in Jupyter Notebook. 


### Resources
Data Source: hawaii.sqlite
Software: SQLite 3.38.2, SQLAlchemy, Python 3.9.12, Jupyter Notebook 6.4.8, Pandas 1.4.2

## Results
Two summary statistics tables were produced using Pandas, one for the June temperatures and one for the December temperatures. 

The summary statistics table for the temperatures in the month of June:

![June temperature summary statistics](https://user-images.githubusercontent.com/111299372/205147323-7c71fe99-1141-477f-93eb-7de14e248590.png)

The summary statistics table for the temperatures in the month of December are: 

![December temperature summary statistics](https://user-images.githubusercontent.com/111299372/205147434-bdacb1f9-6daa-4126-b67b-1620eb8c2572.png)

Results from the summary statistics tables:
* The minimum temperature was found for both months. In June the lowest temperature was 64.0 degrees. In December the lowest temperature was 56.0 degrees.
* The highs were reported to be 85.0 degrees in June and 83.0 degrees in December.
* The average temperature was calculated for each month and displayed as the mean in the summary statistics table. In June the mean was 74.94 degrees. In December the mean was 71.04 degrees. 


## Summary 
Using our two summary tables produced we can compare and contrast the temperatures in June and December. The maximum temperatures for both months were fairly close with June having a high of 85.0 degrees and December having a high of 83.0 degrees. June had a low of 64.0 degrees. The December months on Oahu are a bit colder with a low of 56.0 degrees. On average, June is a bit warmer than December since June has a mean temperature of 74.94 and December has a mean temperature of 71.04 degrees. 
