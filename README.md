# **Introduction**

This project analyzes the global trends in passport power, examining the visa-free access, rankings, and the impacts of various factors, including the COVID-19 pandemic, on the mobility of different countries. Passport strength is measured based on the number of countries a passport holder can visit without needing a visa or with visa-on-arrival. This project uses a combination of Python for data analysis and Tableau for interactive data visualization to provide insights on how passport power has evolved over time and the potential factors influencing these trends.

The key areas of investigation include:

Dramatic improvements in passport power over the years.

Countries that have lost visa-free access or seen declines in their rankings.

The impact of COVID-19 on passport rankings and visa-free access.

Relationships between visa-free access and international relations.

The distribution of visa types and their prevalence across the globe.

# **Methodology**

Data Collection

The data used in this analysis comes from a comprehensive dataset containing information about passport rankings, visa-free access, and visa requirements for countries from 2006 to 2025. The dataset is enriched with country-specific details such as visa-on-arrival, visa-required countries, and electronic travel authorizations (eTA).

Python Analysis

Data Cleaning: We begin by preparing the dataset for analysis using pandas to clean and structure the data, making it suitable for pivot tables, filtering, and aggregation.

Visa-Free Count and Rank Analysis: Using pivot tables, we examine the changes in visa-free access and passport rankings over time. We calculate the difference in rankings and visa-free access from 2006 to 2025, identifying the countries with the most dramatic improvements and declines.

COVID-19 Analysis: We compare pre-pandemic (2019) and post-pandemic (2022) passport rankings and visa-free access to analyze the impact of COVID-19 on global mobility.

Visa Requirements and Access: We analyze the relationship between visa-free access and diplomatic relationships, focusing on countries with the most mutual access. We also evaluate the countries requiring visas for travelers from the USA, Canada, the UK, and India.

Visa Type Distribution: A final analysis examines the different types of visa arrangements (e.g., visa-free access, visa-on-arrival, eTA, etc.) across countries.

Tableau Visualization

To make the insights more accessible, several interactive visualizations were created using Tableau. These visualizations allow users to explore the data dynamically:

Rank Distribution by Country (Year-wise): A world chart illustrating how rankings have evolved for each country over time.

Visa-Free Access Trend: A line chart showing the trend of visa-free access over time, highlighting significant jumps or drops.

Visa-Free Count by Continent: Vertical bar charts showing how visa-free access counts differ by continent for each year.

Rank Distribution by Continent: A treemap visualizing the distribution of ranks by continent.

Top Countries by Visa-Free Access: Horizontal bar charts displaying the countries with the most visa-free access, year by year.

Rank vs. Visa-Free Count: A scatter plot comparing rankings to the visa-free count over time.

Visa-Free Access Trend by Continent: A line chart showing the trend of visa-free access for each continent.

Dashboard

A comprehensive dashboard combining the visualizations mentioned above allows for an interactive and comparative view of global passport power trends. This includes:

World chart for rank distribution by country.

Treemap for rank distribution by continent.

Vertical bar chart for visa-free count by continent.

Horizontal bar chart for top countries by visa-free access.

# **Results**
Dramatic Improvements in Passport Power

Countries with the largest improvements in rankings or visa-free access are identified. Some countries show a significant rise in their rankings over the years, while others have made notable advancements in the number of visa-free countries they can access.

COVID-19 Impact

The COVID-19 pandemic has caused notable disruptions in passport rankings. While some countries have seen a decline in rankings due to strict border controls and travel restrictions, others managed to improve their rankings or visa-free access post-pandemic.

Visa-Free Access Trends

The data shows clear patterns of increased visa-free access for certain regions over time, particularly in Europe and some parts of Asia. However, there have also been setbacks for countries with deteriorating diplomatic relations or changing border policies.

Visa Requirement Trends

The study also found that visa-on-arrival policies and electronic travel authorizations (eTA) are becoming increasingly popular, especially in regions like Africa and the Middle East.

Strong Relationships and Mutual Visa-Free Access

Countries with historically strong diplomatic ties tend to offer mutual visa-free access, particularly within regions like the European Union and parts of South America.

# **Conclusion**

This analysis provides a comprehensive overview of global passport power, highlighting both the improvements and declines in visa-free access and rankings. It underscores the importance of diplomatic relationships and the evolving dynamics in global travel policies, especially in the wake of the COVID-19 pandemic. The results of this study offer valuable insights into how countries' passport strength has changed over time and how these shifts are influenced by political, economic, and health-related factors.

Moving forward, this analysis can be extended by incorporating more granular data, such as travel restrictions related to political tensions or natural disasters, to better understand the dynamic nature of global mobility.
