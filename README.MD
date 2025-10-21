# 🚲 Cyclistic Bike-Share App Data Analysis


## 1 Goals
This project analyzes the differences in bicycle usage between Annual Members and Casual Riders of the Cyclistic bike-share program. The primary business goal is to identify distinct behavioral patterns that will inform a new marketing strategy aimed at maximizing annual membership conversions.
So the main questions to answer are:

- What is the overall distribution of our user types (Members vs. Casuals)?

- Which user group is the most active in terms of total ride volume?

- What are the key differences in ride duration for each group? 

- How does the usage vary across the days of the week for each user type?

- How does hourly usage distribution differ between Members and Casual Riders?


## 2 Data

The project utilized Cyclistic’s publicly available historical trip data, specifically focusing on the first quarter of 2019 and 2020 to capture usage patterns.



| Category | Tools | Purpose in Project | 
|---|---|---|
|  [Data Cleaning](https://github.com/bielmc11/Data_analysis_bike_app/blob/main/cleanning_2020.ipynb) | Python (Pandas) | Merging quarterly CSV files, data cleaning, filtering outliers, and feature engineering (calculating ride duration, day, and hour). |
|  [Data Analysis](https://github.com/bielmc11/Data_analysis_bike_app/blob/main/analysis_2020.ipynb) |  | A project close to 🏡 home. Inspired by Alex Freberg's [Data Exploration Project](https://www.youtube.com/watch?v=qfyynHBFOsM&list=PLUaB-1hjhk8H48Pj32z4GZgGWyylqv85f&index=1), I analysed global and local Covid-19 cases & the impact on Malaysia stock market from Jan 2020 to Jul 2021 using SQL and Tableau. |  
|  [Visualization & Storytelling](https://public.tableau.com/app/discover) | Health analysis | I answer business questions wit.... |  



## 3 Data Processing
In this step mainly:

- Deleting unnecessary columns
- Handling missing values 
- Handling datetimes formats
- Creatin a new column with the duration of the trip




## 4 Analysis
After the data processing, the data was analyzed using the following steps:

  - Member users are the most active users
  - Casual spend more time on trips than casual users
  - Casual users are more active in the weekend
  - We can see a pattern in the trips of membership users, they use more trips to go to and come from work.


## 5 Recomended actions