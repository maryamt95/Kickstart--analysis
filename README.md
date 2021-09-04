# Analysis of Kickstarter Campaigns

## Overview of Project
Louise, an aspiring playwright successfully received funding from a fundraising campaign for her play. Now, Louise wanted to know how different campaigns in the category of theater and more specifically plays performed based on their launch dates and their funding goal. We have a dataset of past Kickstarter campaigns with various observations and measures which was utilized to analyze how such Kickstarter campaigns similar to Louise’s performed in relation to when they were launched and how much goal they had set. This report provides analysis and visualization to summarize the conclusions made from the data set on past Kickstarter Campaigns.
### Purpose
The Purpose of the project is to help Louise understand how previous fundraising campaigns performed in relation to their launch date and funding goal by analyzing a data set on past Kickstarter campaigns similar to her campaign.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://github.com/maryamt95/Kickstart--analysis/blob/main/Theater_Outcomes_vs_Launch.png)

From the data analysis and the line chart of “Theater outcomes based on the launch date” we can see that May is the best time to launch such campaigns. Campaigns launched between September to March are the least successful. Although, there are a high number of failed campaigns in May, it could be attributed to the fact that a total of 166 theater campaigns were launched that month which is the highest across all the other months.
## Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://github.com/maryamt95/Kickstart--analysis/blob/main/Outcomes_vs_Goals.png)

From the line chart “Outcomes based on Goal” we can observe that campaigns for plays which had a goal of less than $1000 and just below $5,000 were the most successful having a success rate of 73%. On the other hand, plays which had a goal between $35,000 and $40,000 also had a good success rate of  67%. This can indicate that other than just the fundraising goal there could be other factors that play an important part in having a successful campaign. The most unsuccessful campaigns are the ones which had goals over $45,000.
## Challenges and Difficulties Encountered
The Kickstarter data contained unreadable launch date data, which needed to be converted from UNIX to a readable standard data. In addition, we just needed the year to do our analysis on launch date. To solve this, the launch date column was further extracted by using the YEAR function in Excel so that we could quickly extract the data for the analysis.

## Results
We can make the following conclusions from Analysis of Outcomes based on Launch Date:

*	May is the most successful month to launch a Kickstarter campaign for a play.
*	September to March are the least successful months to launch a campaign.

We can make the following conclusions from Analysis of Outcomes based on Goals:

*	Having a low fundraising goal below $1000 has the highest success rate.
*	Factors other than just a low goal amount also influence the success rate of the campaign as we observed that even higher goal amounts of $35000-$45000 have a high success rate.


There are some limitations of this data set. 
*	The data set has Goal and Pledged amounts in various currencies and adjustments for the currency exchange rate has to be made to paint a more accurate picture.
*	The dataset included several Kickstarters that were still alive during analysis. This may be a limitation since that data could not be used to determine success or failure.
To better understand the correlation of the Fundraising Goals and launch date with successful campaigns we can calculate central tendency measures such as mean, mode and median and also the spread of the data through variance and standard deviation.


