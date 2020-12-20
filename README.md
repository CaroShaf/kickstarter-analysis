# Analysis of Kickstarter Theater Fundraising Campaigns
## Overview of Project:  Kickstarter funding analysis for Louise for plays and musicals

### Purpose 
This analysis is to determine recommendations for Louise for crowdfunding her play, Fever, in the US, which she estimates will need $10K.  She is also interested creating a musical in GB with a potential initial goal of 4K pounds. Using data from Kickstarter to look at both successful and failed campaigns for similar projects, analysis and results are presented here.

### Analysis and Challenges
The data for this study was acquired from Freddy Rayes Data Consultants from a subset of data from Kickstarter.  Data analysis was performed using Microsoft Excel 2019 by Carolyn Shaffer.  The range of fundraising projects was enormous, but relevant data for theater productions, all over the world, was statistically significant, including some specific plays of interest to Louise.  No analysis could be performed on the outcome of live campaigns, though there are some live campaigns noted, which may have concluded by the time of this study's end.  Also, though Goals were included for Live campaigns, as well as for Cancelled campaigns, Outcomes of either were not.  Some data points were considered "outliers" because they were much larger (or less than) than 1.5xIQR(interquartile range) the upper Quartile (or lower Quartile) and thus discarded.  This is noted where applicable.

### Analysis of Outcomes Based on Launch Date
Kickstarter is an all-or-nothing endeavor.  Successful campaigns meet or exceed their goals and receive the amount of money pledged.  By definition, a failed project is one that doesn't meet its goal, and is therefore unfunded at any amount.  Those that pledged to an unsuccessful campaign, do not get charged, and the campaign receives nothing.  Again, we are not considering the Outcomes of Cancelled or Live campaigns, but their Goals are part of that average.

A brief look at all categories of crowdfunded creative projects in Kickstarter show that Louise is on the right track choosing to pursue funding for a theater project there.  By far more theater projects are attempted in Kickstarter than any other category.  Music is the next most pursued project type, but with less failed outcomes than theater, it is closely aligned with numbers of successfully funded projects.

[Bar Chart of Parent Category by Outcomes] (images/Parent_Category_by_Outcomes.png)

Focusing solely on Successful and Failed Theater campaigns, May is the best time of year to start a campaign.  Kickstarter's own recommendation for all campaigns is for a duration of 30 days. (https://help.kickstarter.com/hc/en-us/articles/115005128434-What-is-the-maximum-project-duration-) so running a campaign from May 1 - June 1 or May 15 - June 15 would be advised.

[Line Chart of Outcomes by Month](images/Outcomes_by_Month.png)

### Analysis Based on Outcomes and Goals
Over 60% (61.4%) of Plays, specifically, were successfully funded through Kickstarter.  Knowing the best time of year to start a campaign, and knowing that most campaigns are successful, the failed campaigns (37.5%) were looked at more closely to see what differences could be discerned to make Louise's campaign one of the successful ones too.  When looking at the data distribution of both the successful and the failed US campaigns for plays, we saw that their very large standard deviations, relative to their IQR (interquartile range) had some very large goals and also some large pledges that were driving the data distributions and throwing it off.  When correcting for these outliers, and producing a Box and Whisker Plot, it shows that the most successful Kickstarter campaigns in the US, have a mean goal of $4,378 and the mean amount pledge at slightly higher at $4,572.

The average number of backers for a successful campaign of this size is 113, with an average donation of approximately $80.  This total is closer to $9K, not the mean of $4,378, as noted above, and in the accompanying chart.  This is due to the fact that although the outliers that exceeded 1.5 times the upper quartile were discarded, there were still quite a few campaigns in the $10K-$12K range that were successful, pulling this average up.  However, it should be noted that although these few successful campaigns in this goal range performed at the level of Louise's target goal, they are atypical and are more likely to result in a failed campaign the where average failed goal is $10,544.

[Box and Whisker Plot of Goals & Pledged US Plays](images/Goals_&_Pledged_US_Plays.png)

Also, Louise noted that she was interested in the success of five different plays she attended in Edinburgh.  These plays together had an average goal of $2,100 and slightly exceeded their goals with an average of approximately 62 backers with an average donation of $40.

Louise's interest in musicals in Great Britian reveals another caution.  This Box and Whisker Plot will reveal that her goal of 4K GBP for a musical in Great Britain may be slightly high.  The median goal is only $1,375 and the average is thrown way off at about 2,090 GBP due to an outlying successful goal of 10K.  Again, due to this successful campaign and its successful pledges, the average pledge is $2,275, making it even higher than the average goal by almost 200GBP.

[Box and Whisker Plot of Goals & Pledges GB Musicals](images/Goals_&_Pledges_GB_Musicals.png)

### Recommendations Based on Analysis and Challenges
Based on the above analyses, recommendations include:
* Start a campaign in the US for a play in May and run it for 30 days
* Set a goal for a US campaign for a play in the range of $4K, down from the goal of $10K
* Consider lowering the goal of 4K GBP to 2K for a musical in Great Britain

These recommendations are in line with statistics from Kickstarter's own web site at:
https://www.kickstarter.com/help/stats?ref=global-footer
72.5% of successfully funded theater projects are in the range of $1K-$9,999.  Louise will find success by staying well under $10K for her play in the US and well under her musical in GB and pay attention to the time of year that she starts her short campaigns.
