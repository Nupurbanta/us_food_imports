# U.S. Food Import Analysis


## Table of contents
* [General Info](#general-info)
* [Motivation](#motivation)
* [Technologies](#technologies-used)
* [Data Sources](#the-data)
* [Data Questions](#data-questions)
* [The Process](#the-process)
* [Cleaning Data](#cleaning-data)
* [Link To Dashboard](#link-to-dashboard)



## General Info
For my capstone project I’d like to analyze U.S. food import trend-based amount spent, volume and effect of growing population, inflation and recession. At least 20 years of annual data are included, enabling users to track long-term growth patterns.

## Motivation
I'm excited about this project on U.S. food imports because I'm curious about where our food comes from and how it has changed over time, especially considering inflation. I want to explore why the prices of different foods vary and what role inflation plays in this. It's like a journey into the history of our food and understanding why some things cost more now than they did before.

 ## Technologies Used

### Python
-	Jupyter Notebooks
-	Pandas
-	Numpy
-	Webscraping and Beautiful Soup
-	Data Cleaning
-	Analysis

### Excel
-	Pivot Tables
-	Filtering
-	Cleaning Data
-	Coverting .xlsx to .csv

### Power BI
-	Graph and Chart Creation
-	Dashboard
-	Power BI Story

## The Data

ers.usda.gov: **[us-food-imports](https://www.ers.usda.gov/data-products/us-food-imports)** <br>
usinflationcalculator.com **[current-inflation-rates](https://www.usinflationcalculator.com/inflation/current-inflation-rates/)** <br>
multpl.com **[united-states-population](https://www.multpl.com/united-states-population/table/by-year)** <br>
wits.worldbank.org **[United States Food Products Imports by country in US$ Thousand 2021](https://wits.worldbank.org/CountryProfile/en/Country/USA/Year/LTST/TradeFlow/Import/Partner/by-country/Product/16-24_FoodProd#)** <br>

## Data Questions

•	U.S. Spent on food imports over the years.

•	Component Total U.S. Food Import value and volume across diverse food groups.

•	U.S. Annual food inflation over the years.

•	Population vs total food import.

•	Top 10 U.S.  food import countries.

•	U.S. food import trend by country over the years.


At least 20 years of annual data are included, enabling to track long-term growth patterns.



## The Process
Collected three excel sheets from ers.usda.gov,multpl.com,wits.worldbank.org. 

Webscrape usinflationcalculator.com using python and Beautiful soup. Collected csv's to clean and use for data


##  Cleaning Data

### Python
-  Changed rows to columns using transpose.
-  Dropped extra columns I did not need.
-  Deleted years that were unusable.
-  Merged data frames to create one continous dataframe to show Population and U.S. food import.
-  Remaning the columns.
-  Chanded Data type.
-  Loading data into Power bi, building dashboards-

### Excel
-  Removed extra rows above data and header row in .xlsx files from wits.worldbank.org



## Link To Dashboard
- Power BI Public: **[US Food Import Analysis](https://app.powerbi.com/view?r=eyJrIjoiNjEwMzcyMWMtOTZlOC00MDk0LWJhMDUtNWQ1MWFjZDgzNjI4IiwidCI6IjEwMWRhNTg3LTE4NDMtNGY1Mi04YjhhLTE3YjA2OWM2NmQzMyIsImMiOjJ9)**<br>
