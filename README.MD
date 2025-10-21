🚲 Cyclistic Bike-Share App Data Analysis


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


Tools UsedTool / ResourcePrimary FunctionKey OutputCyclistic DataRaw data source for all trip information (start time, end time, user type, etc.).Unprocessed CSV files.Python (Pandas)Data Cleaning, Transformation, and Aggregation. Used to merge files, handle outliers, and calculate new features like ride duration and day/hour of the week.A clean, summarized CSV file ready for visualization.TableauVisualization and Storytelling. Used to create professional, interactive charts and a unified dashboard based on the key findings.Final Project Dashboard (Visual Report).GitHubVersion Control and Documentation. Used to host the final code, data summary, and this project report (README).Complete Project Portfolio Piece.


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