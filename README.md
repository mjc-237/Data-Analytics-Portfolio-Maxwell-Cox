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


**Tableau**


**Power BI**

## Get in touch
