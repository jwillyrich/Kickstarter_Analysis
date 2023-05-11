
# Kickstarter-Challenge

## Overview of Project
The client Louise has a play Fever which came close to its fundraising goal in a short time. Louise is now looking into insights on how different campaigns fared in relation to their launch dates and their funding goals.
The aim of the project is to perform data analysis using the dataset given in the excel spreadsheeet to answer some questions. 
### Purpose
The purpose of the project is to provide the client with an insight into the data provided. We will be looking at campaigns launched in which month yield the most success and what should be the optimal goal for their fund raising. 
This analysis should help the client creat successful campaigns and raise money through the campaigns.
## Analysis and Challenges
Analysis was done to gain insight into two problems. First the Campaigns success rate/Outcomes vs the launch time. 

For the first analysis of theater outcomes vs launch date, the given dataset had to be beefed up with new columns. The dataset had the launch date column in EPOCH time which had to be converted to excel date format (MM/DD/YYYY or the excel data serial number). The new column holding this converted data is called the 'Date created conversion'. The purpose of this column is to derive data information for the analysis. The new column also helps us in creating the year column as well as grouping the data by month in the pivot table. For the analysis we created a pivot table from the existing dataset in a new worksheet. this table provides the outcomes with respect to the launch month of the campaign. The pivot table also provides two filters 'Parent Category' and 'Year' to look further into the data. After creating the pivot table, a line graph was plotted for theatre outcomes versus months. 

For the second analysis for Outcomes based on Goals, a graph for Outcomes Vs Goal had to be plotted. From the given dataset we created a new table containing the goals, number successful, number failed, number canceled, total projects, percentage successful, percentage failed and percentage canceled columns. Values for each of the columns had to be populated with regards to the goals. After calculating the values for all the columns, a line graph was plotted for outcomes Vs goals.

### Analysis of Outcomes Based on Launch Date
Here is the graph for Outcomes Vs Launch Date. 
![](resources/OutcomesVsLaunchDate)

After looking at the graph for outcomes vs Launch Date the success rate percentage was higher in the month of May-June with an average success percentage of 66%, when compared to the remaining months the averages success rate for other months is 59%. The highest failure rate was seen for the month of December with only 49% campaigns being successful. 
Another observation from the data is that most plays are cancelled in the month of January, around 7% of the plays see cancellations in January. 

The recommendation to the client would be to launch more campaigns during the months with the most success which are  May, June and July. 

### Analysis of Outcomes Based on Goals
Here is the graph of outcomes based on Goals 
![](resources/OutcomesVsGoals.png)

Looking at the graph plotted for the Outcomes vs Goals it shows that it is more likely to have a better success rate for campaigns with goals below $5000.
Looking at the graph the success percentage for campaigns with goal ranges of $45000 - $49999 is 0% and the success rate for campaigns with goals of $50000 is at 13%. These look like inconsistencies which might be the result of insufficient data or very little data. For example, for the goal range of $45000 to $49999 we have only one campaign when compared to 169 campaigns for the goal range of $5000-$9999. 

### Challenges and Difficulties Encountered
There are a few challenges that stand out but the one I will discuss is that the data is not in a analysis friendly format. For example, the category had to be split into parent category and subcategory and the time provided was in EPOCH instead of excel format.

It was challenging converting the launch date from epoch time to excel date format (MM/DD/YYYY or excel date serial numbers). 

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
  The success rate percentage for launching a play in the month may is 66.9%. The months of May, June and July seem to be the best months to Launch new campaigns. 
  From the graph we see that the failure rate percentage is higher in the month of December. 


- What can you conclude about the Outcomes based on Goals?
The Outcomes based on Goals shows us that there is a good success rate for the goals below $5000. 

- What are some limitations of this dataset?
  Looking at the bar graph for number of campaigns in each goal range, we can determine that there is insufficient data for doing the analysis. Due to this the results may be skewed and not accurate to make an accurate conclusion. For example, for the goal rang of $45000 to $49999 we have only one campaign when compared to 169 campaigns for the goal range of $5000-$9999. 

- What are some other possible tables and/or graphs that we could create?
  Graph for the Year VS Outcomes, One additional Table with Year & Outcomes and Bar graph for Total projects vs Goals
  
  
