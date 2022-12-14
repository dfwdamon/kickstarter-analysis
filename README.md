# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of the analysis is to provide Louise (client) with an opinion on how different campaigns faired in relation to their launch dates and their funding goals.  The clients play _Fever_ came close to its fundraising goal in a short amount of time and additional analysis based on other performances from the Kickstarter dataset were assessed in order to determine and visualize those campaign outcomes based primarily on launch dates and funding goal data.  

## Analysis and Challenges

An analysis was performed using the Kickstarter dataset of crowdfunding projects. This data set contained historical data of various US region projects covering categories such as film, music, games, technology, theater, video and other subjects, where money was raised in order to produce and present numerous public and private performances.  These performances included a large set of approximately 41 subcategories of entertainment covering animation, documentary, drama, music, musicals, plays and television productions.  The analysis utilized Excel for manipulation and review of the dataset and focused on US based campaigns that were historically successful, failed and canceled for the theaterical plays category.  

### Analysis of Outcomes Based on Launch Date

The analysis of outcomes based on launch date looked at the parent category of theater plays for all US campaigns and all years of data available.  The data was filtered to include the successful, failed and canceled campaigns and summed these up on a monthly basis in order to identify when the most successful months of campaign launches occurred.  See the resulting line chart of the **Theater Outcomes Based on Launch Date** below.
          
![Line Chart 1](resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

The analysis of outcomes based on campaign goals looked at the same parent category of theater plays for all US campaigns and all campaign amounts.  The data was counted and grouped by 12 varying goal amounts for the successful, failed and canceled campaigns.  The total number of projects were summed and the percentage of successful and failed campaigns by goal amount were used to identify the most successful campaigns by the dollar amount of goal category.  See the resulting line chart of the **Outcomes Based on Goal** below.

![Line Chart 2](resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
The data was filtered and analyzed using a variety of excel functions such as `COUNTIF`, `SUM`, PivotTables, grouping of data and Line Charts to visually present the results of the analysis. Challenges included getting the functions to present the data in specific order and manipulation of the Excel tools to adequately and effectively present the data in a valuable and helpful manner.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Two conclusions from the analysis of the Theater Outcomes by Launch date were One; the outcomes of successful theater campaigns had occurred during the three months of the year being May, June and July.  This is the period when the most campaigns were successful.  Second; the lowest period of successful campaigns occurred during the end of year in the months of November and December. 

- What can you conclude about the Outcomes based on Goals?

The analysis of outcomes based on goals revealed that of the campaigns, the highest percentage of successful campaigns were those that had campaign goals in amounts of $5,000 or less.  76% of all successful campaigns were in this range, and 73% of the campaigns with fundraising goals of $1,000 to $5,000 were successful.  Fore failed campaigns, those with fundraising goals between $15,000 to $50,000 or more, had a 50% change or higher of failure. Campaigns in the 45,000 or higher had resulted in a nearly 100% chance of failure. 

- What are some limitations of this dataset?

The analysis revealed the dataset is limited in the following ways: The dollar amount of the theater campaigns alone is no guarantee for success.  Other factors may be contributing to the successful outcomes.  This is also evident in the outcomes based on goals, as there were failed campaigns across all fundraising goal levels, with those failing the most being fundraising goals  amounts that were significantly higher than the successful campaigns.
          
The data does show strong support for successful outcomes based on launch date, and the summer months data supports this time period advantage of the theater campaigns.

- What are some other possible tables and/or graphs that we could create?

Additional tables or charts to support the analysis of the dataset for the client would include those that assess all categories of successful campaigns and also drill down into those categories by launch date and goal amount.  Also, it would be wise to look more closely at the successful campaigns and the specific names (and blurb information) of the performances in order to isolate the most popular performances based on title and content being presented.  This could identify a subset of popular theatrical or other performances that are most successful in a designated fundraising range, and then be used to focus on creating only those specific titled performances at a lower cost.  
