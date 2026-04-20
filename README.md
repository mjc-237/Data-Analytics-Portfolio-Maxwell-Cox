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


## World Database SQL Analysis | MySQL

**Tools:** MySQL Workbench, SQL  
**Skills Demonstrated:** Database design, ERD creation, SELECT queries, filtering, 
sorting, aggregation, pattern matching

This project covers two connected areas — designing a relational database schema 
for a retail business, and writing SQL queries against a real-world dataset.

**Database Design**

The first part involved designing a star schema for a small corner shop with a loyalty 
programme. The schema was built around a central Sales fact table with dimension tables 
for Customers, Products, Categories, Suppliers, Stock Level, Loyalty Accounts, and Sale 
Items. Relationships between tables were defined using primary and foreign keys, and the 
full schema was mapped out as an Entity Relationship Diagram (ERD).

![Retail Database ERD](retail_erd.png)

**SQL Querying**

The second part involved querying the World database in MySQL Workbench across a range 
of real-world business scenarios. Queries covered finding the country with the highest 
life expectancy, identifying cities by population thresholds, filtering city names using 
pattern matching, sorting results, and using aggregate functions to compare populations 
across countries.

![SQL Queries and Results](sql_queries.png)

**Example queries written:**
```sql
-- Country with highest life expectancy
SELECT name, lifeExpectancy FROM country 
ORDER BY lifeExpectancy DESC LIMIT 1;

-- Cities with population over 2 million
SELECT name, population FROM city 
WHERE population > 2000000;

-- Cities starting with 'Be'
SELECT name FROM city WHERE name LIKE 'Be%';

-- Top 10 most populated cities
SELECT * FROM city ORDER BY population DESC LIMIT 10;
```


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
