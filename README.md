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

I wanted to discover the story behind what we spend on importing food. Understand how the number of people and the total food we import are connected. Explore the favorite foods with the Top 10 Food Imports, and learn about the rising or falling prices with Food Inflation. 


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

U.S. Spent on food imports over the years

Component Total Food Import chart

Average U.S food import volume across diverse food groups

Average food inflation over the years.

Population and total food import.

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
- Power BI Public: **[US Food Import Analysis](https://powerbi.com)**<br>
