# An Analysis of Kickstarter Campaigns
## Performing Analysis on Kickstarter Data to Discover Trends
---
---
Here we analyze a broad tranche of Kickstarter data, paying special attention to data on theatrical and musical productions in order to glean useful information about what makes campaigns succeed or fail.  

The chart below shows a notable uptick in the number of successful campaigns launched in May - June. It also shows that fewer kickstarter campaigns launched in September and particularly December succeed.

![Outcome Based on Launch Date.png](https://github.com/brendan-oi/kickstarter-analysis/blob/main/Outcome%20Based%20on%20Launch%20Date.png)

Of the Edinburgh Festival Fringe kickstarters that that we examined, all had a goal of £4,000 or significantly less. In fact the mean and median were £2,100 and £2,000 respectively and only one had goal of more than £2,000, demonstrating that campaigns can be successful and result in inspiring productions with relatively modest goals.

Zooming out to theater productions more broadly, failed campaigns in this category set substantially higher fundraising goals than successful campaigns. Of course, higher goals might not be the only reason these campaigns fail: the mean and median pledged amounts are much lower for failed campaigns than for successful ones, but the correlation of higher goals with lower success rates is impossible to ignore. 

![GoalvPledgesBritishMusicals.png](https://github.com/brendan-oi/kickstarter-analysis/blob/main/GoalvPledgesBritishMusicals.png)

For the British Musicals evaluated in the chart above the mean campaign goal is close to £4,000, but this is more than even the range of outliers for amount pledged. The median campaign goal is around £2,000, and even this is clearly over the 3rd quartile for the amount pledged.

From all this we can draw the following conclusions:
* Launch between May and June.
* Do not launch in September or December.
* Inspiring productions do not require large goals or large pledged amounts.
* Campaigns with lower pledge goals are more likely to succeed.
* An initial pledge goal > £2,000 is not recommended.
