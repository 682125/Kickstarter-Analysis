# Kickstarting with Excel

## Overview of Project

## Purpose
###The purpose of this analysis was to assist Louise in determining whether there were specific factors in place that would allow this campaign to be a successful project. Louise is an upcoming playwright that wanted to start a crowdfunding campaign for her play “Fever.” Louise’s starting budget is $10,000, and she is hesitant about starting her first fundraising campaign. This analysis will utilize excel to organize, sort, and analyze the crowdfunding data to help Louise identify specific factors that make a campaign successful. 

#Analysis and Challenges

###When analyzing the data for Louise’s campaign, the first looked at was Theater Outcomes by Launch Date. A pivot table was created in excel to analyze this specific data set. The data incorporated was Parent Category, Years, Successful, failed, and canceled. Once the pivot table was completed, the table was converted into a stacked line graph. The graph allowed for a comparison of whether or not a show was successful during a specific month. For example, May was very successful when it came to theater outcomes. 

###Using the data in the Kickstarter set, we determined to assess the percentage of successful, failed, and canceled plays in terms of the funding goal amount. To obtain the percentages, we first had to use the countifs() function in excel. This function would filter the successful, failed, and canceled amounts in the outcome column. The data was also filtered using a specific goal regarding the outcome column. Once the numbers for successful, failed and canceled were calculated, the next step was to calculate the total projects of each row using the sum() function. This would allow the percentages to be calculated for each row in terms of each goal when it came to if it was successful, failed, or canceled. Once all the percentages were calculated, a line graph was created comparing the percentages of successful, failed, and canceled in the specific goal range. The graphs should have an inverse relationship regarding whether the outcome was successful or failed at specific ranges. 

###Some challenges were encountered during the second data set for the outcome vs. goal graph. Using the countifs() and having the correct order or information for the function took much work. The graph that was created does not look like the graph shown, meaning there is incorrect information for the countifs(). Another difficulty was when the pivot table was being created and ensuring the correct information was being used for each section. This problem was overcome, and the pivot table was done correctly. 


# Results
###When looking at the graph for the outcomes for Theater by launch date, it is easy to see what months had a successful lunch date. May, June, and July had the highest success rate compared to the other months. This would allow Louise to plan her campaign to be successful and create the most amount of revenue. Looking at the data set for outcomes based on goals, the graph shows us that plays failed or were canceled at specific funding goal amounts. This is important because even if the show was “successful,” it failed to meet the specific funding range. There needs to be more research on why the show failed to meet the funding goal amount range. Some limitations on the data set are that when it comes to the shows, how long were the shows available to the public? Was it a one-night show, or was it available for a couple of days. This range will give more in-depth information on why the show failed or succeeded. 



