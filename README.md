# An Analysis of Kickstarter Campaigns

## Overview of Project
Performing analysis on Kickstarter data to uncover trends

### Purpose
To help Louise analyze outcomes in relation to their launch dates and their funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/95720986/146844642-0ee54f84-0444-4723-9aef-256f2797374f.png)

Overall, there were more campaigns that were successful by launch date than there were campaigns that failed or were canceled.  The month of May had the greatest number of successful campaigns, with peaks in both February and October.  These same peak months also had peaks of failed campaigns, so we will want to look at goals set for these failed campaigns to see if that came into play for why they failed.

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/95720986/146844618-3000824a-51db-414a-aea0-658cd83d50ca.png)

When goals were between $25,000 and $35,000 or greater than $45,000 the likelihood of having a successful campaign was poor.  While there was no range that was 100% successful there was a range that failed 100% of the time.  Louise should avoid campaigns with a goal of $45,000 to $49,999.  Campaigns that needed less than $5000 in funding performed very well.  

### Challenges and Difficulties Encountered
While creating the graph for outcomes based on launch date, I had a little trouble with sorting and couldn't remember if 'Sort Z to A' was ascending or decending, so I had to do the filter a couple times in order to make sure that it displayed as requested.  When the rows originally showed with more than just the month, I relied on what I had learned during class and dragged the unwanted date categories out of the pivot table fields to only leave month.  This gave me the rows and columns as requested and I was able to create a chart that looked like the example.

While creating the formulas for outcomes based on goal, I ran into some trouble trying to figure out where the second part of the less than argument was in relation to the rest of the formula.  I was unsure if it made a difference.  The formula I wrote gave me the results I was looking for, so I copied the formula and changed the numbers for the goals in each cell instead of writing it new each time to minimize the risk of making a mistake.

## Results
Louise should continue to campaign in the month of May.
Louise should avoid campaigns in December as that is the only month where the number of failed and canceled campaigns combined were greater than the number of successful campaigns.

Goals should not be set for $45,000 or greater.

Some limitations of this dataset include not knowing how many people were approached for a donation and refused.  Who are the people that didn't donate?  Could you approach them differently or with a different parent or sub category and they would be more inclined to donate?  Are the same people donating all the time?  How are people being asked for donations? Email? Telephone calls?  Mailers?  Analyzing what way people prefer to be approached could be beneficial.

A graph that compares the months of a successful campaign to whether the goal was reached or not would help determine which months you should attempt campaigns with a higher goal and which months you should campaign for projects that have a lower goal.  
