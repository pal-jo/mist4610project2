# MIST Group Project 2 - Group 2 71552

# Team Members:
* Ayush Aggarwal, [@ayu086](https://github.com/ayu086)
* Palak Joshi, [@pal-jo](https://github.com/pal-jo)
* Soha Nathani, [SohaNathani16](https://github.com/SohaNathani16)
* Vinay Polaku, [vinay-polaku](https://github.com/vinay-polaku)
* Christine Shen, [@xixi922](https://github.com/xixi922)


# Dataset Description

## Purpose & Use
The dataset we chose, Food Affordability in California (2006–2010), comes from the U.S. government’s open data catalog and was published by the California Department of Public Health as part of the Healthy Communities Data and Indicators Project. It measures the food affordability for female-headed households with children under 18 across different racial and ethnic groups in California. The data covers the years 2006 to 2010 and includes information at the state, county, and city level.

The goal of this dataset is to show how affordable a basic basket of healthy food is, relative to income, for different communities across the state. The affordability metric is based on the cost of food as a percentage of household income — the higher the percentage, the less affordable food is considered to be.

This dataset helps show which communities in California are struggling the most with food costs. By looking at how much of their income different groups spend on food, it displays where the biggest gaps and challenges are. It’s especially useful for researchers, public health workers, and policymakers who want to better understand food insecurity, make fair decisions about where to send support, and track whether things are getting better over time.

## Size and Structure
* Rows: 9,637 (Each row represents a specific racial or ethnic group in a particular California location (such as a city or county) during the reporting period)
* Columns: 23 

## Column Summary & Datatype
  <img width="637" alt="image" src="https://github.com/user-attachments/assets/0715b629-d372-4b2c-a50b-55820137caeb" />  
  <img width="637" alt="image" src="https://github.com/user-attachments/assets/697461d2-f795-4047-98b2-9846806972e0" />


# Description of Questions

## Question #1 - How does the affordability of meals vary across different counties in California?
Understanding meal affordability across counties helps identify communities facing higher risks of food insecurity. It sheds light on social inequalities that impact health, educational outcomes, and overall quality of life. Certain counties may have more vulnerable populations, such as seniors, immigrants, or low-income families, who are disproportionately affected by high food costs. Meal affordability is closely tied to regional economic conditions such as median income levels, employment opportunities, housing costs, and the local cost of living. By studying affordability variations, policymakers and organizations can better allocate resources, design targeted subsidies, and stimulate economic support in the hardest-hit areas. Different counties have diverse cultural compositions that influence dietary needs and food preferences. High costs may limit culturally appropriate food access for certain communities, leading to nutritional deficits or loss of cultural food practices. Understanding affordability ensures that all communities can maintain their food traditions without financial strain.

## Question #2 - How does meal affordability vary with family size in California?
Family size directly impacts household food security. Larger families face greater food demands, and without affordable options, children and other dependents may suffer from inadequate nutrition, impacting long-term health and educational attainment. Analyzing affordability by family size highlights the social needs of larger households, especially those with children or elderly members. Larger families often have higher overall expenses (not just for food, but also housing, healthcare, and education). If meal costs rise disproportionately with family size, it can strain household budgets, increase debt, or force families to make unhealthy trade-offs, such as skipping meals or buying cheaper, less nutritious food. In many cultures, larger family units are common and valued. High meal costs can place additional burdens on culturally traditional households that prioritize family gatherings and shared meals. Ensuring affordable meals supports cultural practices centered on food and family cohesion.


# Data Manipulations

## Question #1 - How does the affordability of meals vary across different counties in California?
For Question 1, the analysis focused on how the affordability of meals varies across different counties in California. We filtered the dataset to include only county-level data, where the geotype is listed as "CTY." Then, we grouped the data by county_name to calculate the average affordability ratio and the average family size for each county. To understand the spread of affordability, we calculated the minimum, maximum, and average values of the affordability ratio across all counties. Additionally, we organized the data by region to prepare for geographic comparisons.

## Question #2 - How does meal affordability vary with family size in California?
For Question 2, we examined how meal affordability varies with family size in California. we plotted the affordability ratio against family size in Tableau using scatterplots. To better understand the relationship, we added trendlines to the plots, which revealed a positive correlation between family size and affordability ratio. Furthermore, we sorted the data by region in Tableau to explore any geographic variation in the relationship between affordability and family size.


# Analysis & Results

## Question #1 - How does the affordability of meals vary across different counties in California?
<img width="484" alt="image" src="https://github.com/user-attachments/assets/c95ffffa-d6d0-4cb0-9753-2eb97d3f9de4" />

The affordability of meals in California counties shows substantial disparities, with affordability ratios ranging from 0.17 to 0.81. This wide range highlights significant inequality in access to affordable food across the state. Counties with higher affordability ratios tend to struggle more with food accessibility, indicating a need for targeted support to enhance food access or provide economic aid.

A notable urban-rural divide is evident in the data. Urban counties like San Francisco and Los Angeles generally have lower affordability ratios, meaning meals are more affordable relative to household income. These areas typically benefit from higher median incomes, better access to food resources, and more developed infrastructure and transportation systems. In contrast, rural counties such as Tulare and Shasta tend to have higher affordability ratios, signaling lower affordability. These regions often face challenges such as limited proximity to agricultural production and underdeveloped infrastructure, which can create food deserts and hinder access to nutritious meals.

## Question #2 - How does meal affordability vary with family size in California?
<img width="565" alt="image" src="https://github.com/user-attachments/assets/eb8451e6-5043-43ce-8600-299cacd0468a" />

The analysis shows a moderate positive correlation between family size and meal affordability ratio, suggesting that larger families tend to face greater difficulty affording meals. This trend is likely driven by the strain placed on fixed or limited household incomes, which are spread thinner as family size increases—particularly within low-income brackets. Additionally, larger households often include more dependents and fewer earners, which increases the economic burden per adult and makes affording meals more challenging.

There are also notable regional outliers, especially in Shasta and the San Joaquin Valley, where affordability remains low even for average-sized families. These regions face multiple compounding issues such as low wages, high poverty rates, and significant food insecurity, particularly among farmworker populations. The lack of food infrastructure in these areas further contributes to the problem, creating what are effectively food deserts.











