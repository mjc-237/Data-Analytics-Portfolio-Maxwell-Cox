# Data-Analytics-Portfolio-Maxwell-Cox


# Hi, I'm Max

## What I work on


## Selected projects 

## County Product Sales Analysis | Excel

This dataset tracks the sales performance of products across several counties in England. 
The data was provided as a raw table with three columns — County, Product, and Sales Volume.

Before any analysis, the Sales Volume column needed cleaning as the values had trailing 
spaces that caused Excel to read them as text instead of numbers. Once fixed, I built a 
pivot table to summarise total sales by county and product, then added a SWITCH formula 
to automatically label each row as High, Medium, or Low based on sales volume thresholds. 
Conditional formatting was applied on top to make the performance bands immediately visible.

**Formula used:**
```excel
=SWITCH(TRUE, C2 > 600, "High", C2 >= 300, "Medium", "Low")
```

![Pivot Table and SWITCH categorisation](pivot_table.png)

**Intro to Python for Data Analysis**


**SQL for Analysts**


**Power BI Dashboards**


## Global Health Insights Dashboard | Tableau

**Live Dashboard:** [View on Tableau Public](https://public.tableau.com/app/profile/maxwell.cox/viz/GapminderDashboard_17745208717160/GlobalHealthInsights?publish=yes)

This project analyses the GapminderHealth dataset covering global health metrics across 
countries and continents from 1990 to 2008. The goal was to identify health trends and 
disparities that a global health organisation could use to inform future decisions.

The dataset contains 6,000 records with fields including life expectancy, BMI, population, 
gender, country, and continent. Using Tableau, I built four individual worksheets and 
combined them into a single interactive dashboard covering life expectancy by continent, 
life expectancy trends over time for the top 5 countries, population distribution by gender, 
and a scatter plot comparing average BMI against life expectancy coloured by continent.

Key findings included a clear positive relationship between BMI and life expectancy, with 
European and Oceanian nations clustering at the higher end while African countries sat 
significantly lower. Japan led life expectancy among the top 5 countries, reaching roughly 
83 years by 2008, and Europe averaged around 75 years compared to Africa at approximately 
55, highlighting a persistent global health inequality.

![Global Health Insights Dashboard](gapminder_dashboard.png)


**Power BI**

## Get in touch
