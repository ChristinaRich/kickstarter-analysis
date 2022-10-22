# Kickstarting with Excel

## Overview of Project
Analysis of the Kickstarter Data was used to help Louise visualize campaign outcomes and how they are correlated with their launch dates and funding goals. 


### Purpose
Louise is particularly interested in the data relating to Theater campaigns, and specifically plays to inform her analysis on her own play, *Fever*. The following charts transform thousands of datapoints into meaningful information to inform Louise's campaign strategies. 


## Analysis and Challenges


### Analysis of Outcomes Based on Launch Date

![ScreenShot](https://github.com/ChristinaRich/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)



### Analysis of Outcomes Based on Goals

![ScreenShot](https://github.com/ChristinaRich/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

The raw dataset was too large to draw conclusions from at first glance, and some data categories were unreadable without advanced computing and calculations. In order to see how the launch dates informed campaign success, we had to convert the raw data from Linux timestamp formatting to a standard date format that was readable to the average person. 

It helped to parse the data using Pivot Tables. There are many columns in this workbook that do not immediately useful to Louise's analysis. Pivot Tables were useful to look at isolated variables to determine if there was a meaningful trend, without getting lost in the plaque of thousands of rows and dozens of columns. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Campaigns launched in May and June had the highest number of successful campaigns. These months also had the highest number of campaigns that were launched, but the percentile of successful campaigns of the total campaigns for each month were also highest in May and June (67% and 65% respectively). The data seems to indicate that these would be the best months to launch a campaign.
December was the month that had the lowest number of launched and successful campaigns. The mean success rate for all months is 61%. only 49% of campaigns in December were successful. This would be the worst month for Louise to launch her campaign. 

- What can you conclude about the Outcomes based on Goals?
The graphs indicate that campaigns for plays with smaller goals are associated with higher rates of success. Louise should prioritize setting realistic, and smaller goals.  There is a spike towards the higher tail of the graph but I'm not convinced that it is meaningful because the population of outcomes for higher campaign goal amounts is significantly smaller than the lower amounts. I don't think we can confidently conclude that a sample size of 1 to 11 (which includes every campaign with a goal of 25K or more) would give us a clear understanding of the relationship between the goal and outcome for these bifurcations. 

- What are some limitations of this dataset?
The population of campaigns with goals in the higher ranges, particularly 45K-50K, is so small that I don't think the conclusions are necessarily accurate. There was only one sample for this fragment of the total population and because it failed, I the graph shows that all campaigns at this level fail. I do not think that it is meaningful to include. 
Location is also very general. Especially for a US campaign, the state might have a lot more to do with the overall success and total amount pledged for a particular campaign. Understanding that it's hard to do with a data set from across the globe, it might be more meaningful to distil the data further for US campaigns based on state. A campaign in New York could have significantly different results than another campaign in Kentucky. 

- What are some other possible tables and/or graphs that we could create?
There are two variables for the Theater Outcomes Based on Launch Date, but our graph really only makes one of them immediately apparent. I think that changing the graph to a stacked bar graph would help illustrate how many total campaigns were launched each month, so that the reader could look at the percentiles for success and failure. For instance, looking at the difference between August and September, we see that the number of successful campaigns decreased from 72 to 59, but the percentile of successful campaigns, which aren't shown, actually increased from 59% to 61%. 
