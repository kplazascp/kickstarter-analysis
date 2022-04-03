# An Analysis of Kickstarter Campaigns
In this written analysis for Louise, we are evaluating the outcomes different fundraisers for theater campaigns.

## Overview of Project

The analysis is made for Louise, a client who launched a fundraising campaign for her play. For that reason, you will find the following analysis, focusing on the category of theater and subcategory of plays for different fundraising campaigns where we will compare the outcomes (meaning if the campaign was or not successful) based on launch dates, goal amounts and years.

### Purpose

The purpose of this analysis is to help Louise understand what are the variables that affect the outcome of a fundraising campaign for being successful in the theater/plays subcategory.
We will dive in variables like launch dates, goals and backers to give Louise a complete understanding of the different campaigns so that she can create the best strategy for her next fundraisers. The third step we will call "Analysis" which was to create pivot tables and graphs to analyze and visualize all the data to get a better understanding of it. Last but not least, the fourth step will be called "Next steps" where we will evaluate what additional information can help us to add to our existing analysis to be able to improve it.

## Analysis and Challenges

The analysis was implemented in four stages. The first step was to download the data of campaigns and examine the data, the second step was to clean the data and create measures and columns, which we will call "Data preparation" for future references.  

For the first step we downloaded the dataset, which was an Excel file containing the information of all Kickstarter Campaigns with the id of the campaign, the name, goal, outcome, currency, launch dates, category and subcategory. The importance of the first step was to be able to explore the data and see what variables we had, evaluate how the data was presented and, if missing important data to be able to incorporated in the second step.

The second step was the Data preparation, we clean the data (separate category and subcategory to form two separate columns), create new measures and data that will be helpful with the analysis (such as percentage founded, average donation and date conversions) and create new columns that will help our visualizations (Year of campaign).

The third and fourth step we will see in greater detail in the following sections, which are Analysis of outcomes Based on Launch Date, Analysis of Outcomes Based on Goals and Next Steps.

### Analysis of Outcomes Based on Launch Date

The goal of the of Outcomes based on Launch Date was to be able to provide Louise with a visualization of campaign outcomes based on Launch Dates, by creating a graph where we can evaluate if the campaign was successful, failed or cancelled. 

To begin this analysis, we created a new column called Years, so that we were able to fitter our information of launch dates to month and see if the year in which the campaign was launched, changed the outcome of the campaigns. 
To be able to create this visualization we created a pivot table LINK HERE with the months of the campaign and the outcomes of theater campaigns and sorted the results so that the successful campaigns were shown first. We decided to leave Year as a filter to be able to dive deep into further analysis if necessary.

(image here)

In this graph we can see that the highest number of successful campaigns start increasing in May, with the highest point of successful outcomes in May followed by June and July, and in August it is at the same point than May and from September it starts to follow the same pattern of January February and March. 
Also, we can evidence that the highest points of failed campaigns were in the months of May, June, July, August and October, being the highest failed outcomes May and October.
Last but not least, we can evidence that there are very low canceled fundraisers over the year, being the highest point January with 7 cancelations.
To close the analysis of this graph, it is important to look at December, where the amount of failed and successful campaigns is almost the same.

###### Was there a Year where more campaigns were successful?

(image here)

If we visualize the same data of outcomes of campaigns in theater subcategory by years, we can evidence that from 2010 to 2013 all of the campaigns where successful (100%) and from 2014 forward (2014 to 2017) the percentage of successful campaigns is around 60%, which means that 6 out of 10 fundraising campaigns in theater will be successful. 
For the failed fundraising campaigns, we also can see the trend that before 2013 there were no failed campaigns, but since 2014 the average percentage of failed campaigns is around 35%.
This means that out of 10 fundraising campaigns in theater, 6 are going to be successful, 3 are going to fail and 1 is going to be cancelled. 

### Analysis of Outcomes Based on Goals

For the second analysis, we wanted to evaluate the percentage of successful, failed and canceled theater campaigns based on the funding goal amount.
For this analysis we created a table with COUNTIFS() because we divided the goal amount in ranges so that we could analyze in groups the outcomes and not individually. 

(image here)

As we are able to see in the graph, the higher percentage of successful campaigns where on the range goals of less than $5,000 USD (average 74% of successful campaigns) and from $35,000 to $44,900 USD (with 67% of successful campaigns), also with a higher percent of successful campaigns but not as high as the previous goals are the campaigns with goals in the range from $10,000 to $14,999 USD.
The range of goal that had 50% of successful campaigns and 50% of failed campaigns were from $15,000 to $20,000 USD and for the higher percentage of failed campaigns we found them in the goal range from $20,000 to $34,999 and for more than $45,000 USD. 

### Challenges and Difficulties Encountered

The challenges and difficulties that could be encountered are the creation of new formulas and columns added to the analysis, to prevent this, a good advice is to use the excel file attached so that it serves as a guide.
Also, it is important to consider the information you want to display in the pivot table, before locating the rows, columns or values so that it visualizes the way you intended it to look like.

## Results
The final recommendations for Louise are the following:

- The highest amount of successful and failed campaigns was in May, with 111 successful campaigns and 52 failed campaigns. The highest cancelation campaigns were in January with 7.

- In December there are almost the same amount of successful and failed campaigns, with 37 successful campaigns and 35 failed campaigns.

- For the outcomes based on goals, the amount of defined goal plays a key role in the percentage of successful and failed campaigns, where if the range is less than $5,000USD or from $35,000 to 44,900 have the highest percentage of success.

- Some limitations of the dataset are that we have only the data up to 2017, we will need the data from 2018 to 2021 so that we can evaluate of how the months, years and goals affect the fundraising campaigns.
Also, we only have data from 1,066 plays (subcategory) and theater (category) so it would be better if we can get a larger sample, so that we can evaluate if the behavior is still the same.

- We could create a table with ranges of backers and analyze the outcome based on backers. Also, we can zoom in the failed campaigns what were the ranges of percentage founded, to see how close or far, where the results. Finally, we could perform the same analysis in failed or cancelled campaigns, to see if we can find a pattern so that Louise can avoid it.
