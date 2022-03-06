# An Analysis of Kickstarter Campaigns
# Kickstarting with Excel

## Overview of The Kickstarting Analysis

In this analysis we look at how campaigns performed in their funding goals and how they performed relative to their launch dates. We did this by using pivot tables, creating charts, and formulas in Excel. 

### Purpose of the Kickstarting Analysis

We looked at funding goals by month and which campaigns were successful, failed or canceled.  To do this we first created a column with years using “Date Created Conversion”.  Once we had our years, we could create a pivot table that included “Parent Category” and “Years” as filters. This way we could look at how campaigns, specifically for theater, fared from 2009 to 2017.  Our pivot listed months and outcomes, which were filtered by successful, failed and canceled and displayed in descending order.  This allowed us to create a line chart “Theater Outcomes vs Launch”.

### Analysis for Theater Outcomes by Launch Date

The data in the chart showed most of the theater campaigns were successful throughout the years (839 total successful). The data also showed us that the winter months were challenging with fewer successes, while campaigns in the summer months performed better. In total, the canceled campaigns were not significant, only at 37 from 2009-2017.

### Analysis for Outcomes Bases on Goals

Secondly, we looked at the campaign outcomes for plays by the goal amount by creating dollar amounts ranges to better analyze outcomes by goals. Here we used the countifs formula to count the outcomes by range. We then summed each row to get the total projects.  By doing this we were able to calculate the percent of each outcome.  Lastly, we created a line chart and titled it “Outcomes Based on Goals”. 
We were able to see that the most successful campaigns were for goal amounts less than $4,999, with the largest projects in the range of $1,000-$4,999. While the least successful campaigns were above $45,000, however, the total projects for over this amount were only 17. Surprisingly no campaigns for plays were canceled. The highest failed campaigns ranged in the $25,000-$34,999 categories. By simply looking at the graph one can easily see this difference in failed campaigns to successful campaigns in the ranges. 

### Challenges Encountered

The challenge I experienced in my analysis was in the countifs.  First, I had only ever used the countif statement, not countifs. I had to watch the video in the hint a couple of times before I understood it. Secondly issue with countifs was a simple mistake in the formula. I had the wrong signs for less than. I kept thinking I had the wrong ranges, or the order was incorrect, given that the formula was new to me, However, once I slowed down and read the formula carefully, I was able to find the simple error in the formula.  This taught me that sometimes the mistake can be small, but easily overlooked.

### Conclusion and Recommendations

In conclusion, by doing this analysis we know that theater campaigns do best in summer months, with goals being less than or equal to $4,999. Once goals hit about $20,000 there is a 50-50 chance at failing.  We could narrow the information down by country to see if what we stated holds true in the specific country in which we launch the campaign. A limitation in our data is that it doesn’t tell us how to be successful in campaign funding, but it does give us a good understanding of where to start in order to achieve success.
