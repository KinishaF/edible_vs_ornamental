# edible_vs_ornamental
Petals or Produce?
An analysis of Edible and Ornamental Crop Production Across U.S. States

Tableau Dashboard 
Link: https://public.tableau.com/app/profile/kinisha.floyd/viz/PetalsorProduce-AnanalysisofEdibleandOrnamentalCropProduction/HowFoodProductionHasChanged 

Table of Contents
•	Tableau Dashboard
•	Motivation
•	Data Question
•	Sub-questions
•	Known Issues and Challenges
•	Tools & Technologies
•	Data Sources
•	Insights Gained
•	Reflections

Motivation
As someone transitioning into data analytics with a background in community programs and a passion for gardening , I chose this topic to explore how agricultural priorities reflect - and influence - economic and social landscapes across the U.S. Understanding where food is grown, especially in comparison to where it is need most, has real-world implications for addressing food insecurity, equitable resource distribution, and long-term sustainability
By comparing edible and ornamental crop production with population data, poverty rates, income levels, and regional characteristics, this project aims to uncover disparities and patterns that can inform more effective resource distribution, food policy, and sustainable solutions. My hope is that this work contributes to a better understanding of how data can be used to not only reveal gaps in the food system but also inspire innovative strategies to close them.  

Data Question
Which U.S. states grow the most edible and ornamental crops and how do these patterns relate to population size, income levels, and poverty rates?

Sub-questions for Analysis

1.	Trends Over Time
•	How have Edible Crops (acres harvested) and Ornamental Crop production (sales ($)) changed from 2012 to 2022?
2.	Crop Prioritization Over Time
•	How have Edible Crops changed between 2012 and 2022 by commodity (i.e. is the top crop for a state in 2012 still the top crop in 2022)?
3.	State-Level Agricultural Shifts
•	Which states increased or decreased their total acres harvested for edible crops between 2012 and 2022?
4.	Edible and Ornamental Crop Focus
•	Which states produce the highest volume of Edible Crops per capita?
•	What are the top Ornamental Crops in sales dollars ($)
•	Which states generate the most revenue in Ornamental Crops?
5.	Economic Correlations
•	Do states with higher poverty rates grow more food (or less)?
•	Is there a correlation between Edible Crop production and median household income?

Known Issues and Challenges
•	Data Cleaning:  USDA Census data includes placeholder values like “D” (withheld data), which required regex filtering and manual checks.
•	Merging Datasets: Aligning USDA and U.S. Census Bureau data across three different years posed challenges with consistent formatting and state name matching. 
•	Normalization: The value for Edible Crops is measured in acres harvested, whereas the value for Ornamental Crops is measured in sales dollars ($). Therefore, creating per capita metrics (i.e. acres harvested per 100,000 residents for Edible Crops and sales dollars ($) per 100,000 residents for Ornamental Crops) added depth to the analysis and helped surface regional disparities

Tools & Technologies
•	Python / Pandas – Data cleaning, merging, and exploratory data analysis
•	Tableau – Data visualization and dashboard development
•	Canva – to create presentation introduction

Data Sources
1.	USDA NASS Quick Stats - https://quickstats.nass.usda.gov/  
•	Agricultural Census data for vegetables and horticultural commodities (2012, 2017, 2022)
2.	U.S. Census Bureau - https://www.census.gov/ 
•	Population, poverty rates, income, and selected demographic data by state (2012, 2017, 2022)

Insights Gained
•	States like California, Florida, and Washington lead in edible crop production overall, but when normalized by population, smaller agricultural states sometimes outperform larger ones in per capita food output.
•	Ornamental crop sales tended to be higher in states with higher median incomes, suggesting that aesthetic gardening may be more prevalent in areas with higher income.
•	There is often a disconnect between high food production states and areas experiences the most food insecurity, raising questions about the logistics and equity of food distribution.

Reflections
This project was a meaningful step in my transition into data analytics. Coming from a background in community programs and having a deep passion for gardening and food justice, I wanted to work on something that connected data to real lives. Exploring where food is grown, compared to where it’s most needed, allowed me to better understand the relationship between agriculture, economics, and access. 
Along the way, I strengthened my technical skills in data cleaning, merging large datasets, and visualizing insights with Python and Tableau. But more importantly, I learned how powerful data can be when used to tell a story. It helped me further see how analytics can shine a light on disparities that affect communities and how that insight can help drive more informed decisions in the future. 
