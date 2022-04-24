# An Analysis of Kickstarter Campaigns
## Performing Analysis on Kickstarter Data to Discover Trends
---
---
Here we analyze a broad traunch of Kickstarter data, paying special attention to data on theatrical and musical productions in order to glean useful information about what makes campaigns succeed or fail.  

The chart below shows a notable uptick in campaign the success rate for campaigns launched in May - June. It also shows that kickstarter in September and particularly December have a low success rate.

![Outcome Based on Launch Date.png](https://github.com/brendan-oi/kickstarter-analysis/blob/main/Outcome%20Based%20on%20Launch%20Date.png)

Of the Edinburgh Festival Fringe kickstarters that that we examined, all had a goal of less the £4,000. Infact the mean and median were £2,100 and £2,000 respectively, demonstrating that campaigns can be successful and resulting in inspiring productions with relatively modest goals.

Zooming out to theater productions more broadly, failed campaigns in this category set substantially higher fundraising goals than successful campaigns. Higher goals might not be the only reason these campaigns fails: the mean and median pledged amounts are much lower for failed campaigns than for successful ones. 

![GoalvPledgesBritishMusicals.png](https://github.com/brendan-oi/kickstarter-analysis/blob/main/GoalvPledgesBritishMusicals.png)

For the British Musicals evaluated in the chart above the mean campaign goal is close to £4,000, but this is more than even the range of outliers for amount pledged. The median campaign goal is around £2,000, which is clearly over the 3rd quartile for amounts pledged.

From all this we can draw the following conclusions:
* Launch between May and June.
* Do not launch in September or December.
* Inspiring priductions do not require large goals or large pledged amounts.
* Campaigns with lower pledge goals are more likely to succeeed.

Based on the data an initial pledge goal of ≲ £2,000 in recomended.
