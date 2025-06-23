# Power-consumption-analysis(Using PowerBI)
## Project Objective
The aim of this study is to analyze and Optimize power consumption pattern of regions/companies overtime for efficiency, cost savings and sustainability
## Dataset used
<a href="https://github.com/Me1rem/Power-consumption-analysis/blob/main/DATASET..zip">Dataset</a>
## Questions kpis
1. Compare Power Consumption across companies – Which company is consuming the most/least energy over a given period
2. Trend analysis over time – What are the daily or seasonal patterns in energy usage for each company
3. Identify Peak Power Consumption Periods – Are there specific hours of the day when power consumption spikes

Dashboard Interaction <a href="https://github.com/Me1rem/Power-consumption-analysis/blob/main/ONWUPELU%20MIRACLE.pbix">View Dashboad</a>

## Process
The Dataset Consists of 12 tables for each region/Company and they have 2 columns each, one is the load in MW, while the other is the date and time at which the load in MW was recorded

The analysis started off with writing an M code from 1998-2018 that creates a table of hourly timestamps between 1998-2018,then the table was merged with all the region/company loads in MW and the rest of the columns were unpivoted except for the date and time column.

The data types were formatted and standardized, duplicates were removed and blank rows were taken care of.

## Dashboard image
<a href="https://github.com/Me1rem/Power-consumption-analysis/blob/main/POWER%20CONSUMPTION%201.png">View Dashboad</a>
<a href="https://github.com/Me1rem/Power-consumption-analysis/blob/main/POWER%20CONSUMPTION%202.png">View Dashboard</a>

## Key Insights
The time of the day with the highest power consumption across all regions/companies is the evening, this is because a lot people return from work at this hour leading to a spike in use of electricity, that is the use of light, appliances, charging devices and extended commercial operations.

The top 5 region/company and their highest peak loads are PJME,PJM_LOAD,AEP,COMED and NI.This could entail that these regions have a spike in energy demand during some specific time of the day.These peaks may reflect industrial operations, high residential density or limited efficiency controls. Understanding these patterns is essential for grid planning and preventing overload!

There was an all time decrease in power consumption in the month April, May and October this could probably be driven by milder weather conditions reducing the need for air conditioners and possible operation slow down in industrial sectors for mid-year budgeting reviews or preparation for year end holidays. Understanding these seasonal dips can better support demand forecasting and resource allocation.

Non-business hour had a higher power consumption  because people have retired home to rest, there will be increase in appliances use .

The Total Power Consumption across all company/regions is 12bnMW.The average Power Consumption across all company/regions is 11.21k MW.There are a total of 12 regions/companies in the dataset.The Maximum/peak load across each company is 62k MW

## Conclusion.
Overall, these insights highlight the importance of time-based, region-specific, and seasonal factors in shaping energy demand. They underscore the need for:
Load forecasting and demand response strategies

Energy efficiency initiatives in peak regions

Data-driven planning to optimize resource use across different times of day and year

These findings provide a foundation for Tobi Power Innovations to enhance grid reliability, reduce operational costs, and support sustainable energy management

