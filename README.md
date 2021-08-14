# An Analysis of Kickstarter Campaigns
## Overview of the Project: Kickstarter funding analysis for determine optimal campaign timing, donation ask amount, campaign length and fundraising goals 

## Analysis

### Filtering down the data
When looking at the data, I drilled down to the data specific and relevant to the project (Theater/Plays). It was important to filter out the irrelevant data so none of my results were skewed by campaigns that did not relate to the current analysis. 

### Summarizing data to see a basic overview
In using pivot tables, I was able to calculate averages for campaign length, fundraising goal, $$ pledged, donation amount, backers and average % over goal amount. This allowed me to get an overall summary view to compare successful and failed campaigns and see where they differed. 

![Average%20Play%20Result%20Summary.png](https://github.com/melaniekelsey/kickstarter-analysis/blob/main/Resources/Average%20Play%20Result%20Summary.png)

### Graphing the data
The next thing that I examined was outcomes based on goals by graphing out the percentage of campaigns by goal bucket. The highest percentage of successful campaigns were smaller goal amounts. The highest percentage of failed campaigns were in higher amounts. 

The final thing that I examined was the outcomes based on launch date. In graphing it out, you can see a significant spike in successful campaigns launched in May. There is a clear slow decline in successful campaigns following that, with smallest amount in December. Maybe people are less likely to donate during the holiday season with gifts to purchase. 

## Challenges
I didn't have too many challenges with this project. The most challenging items were adding images to this Readme file. 

On a data analyst's side, it might be challenging to determine which factors are the most important to look at when determining details of a Kickstarter campaign. We don't know about Louise's location or about the genre of her play. If we could get more specifics we would have the ability to compare similar Kickstarter campaigns that would correspond to her goals. 

## Results

### Conclusions based on Theater Outcomes by Launch date
Based on Theater Outcomes by Launch date, I think it is clear that May is the right time to launch the campaign. The line graph clearly shows that the highest count of successful campaigns were launched in May. The worst time to launch seems to be December with the smallest amount of successful campaigns. 

![Theater_Outcomes_vs_Launch.png](https://github.com/melaniekelsey/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Conclusions based on Outcomes based on goals
When examining the outcomes based on goals, this is a trickier thing to determine. The highest % of successful campaigns are in the $0-$4999 range. The highest % of failed campaigns are in the $45000+ range. Something that might skew the data is that there are 353 failed campaigns compared to 694 successful campaigns, so you are not necessariliy comparing apples to apples. The one thing I am sure of, is that keeping the fundraising goal smaller seems to be the best tactic to hit your goals. 

![Outcomes_vs_Goals.png](https://github.com/melaniekelsey/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Limitations of the data set
I believe that Louise should do some further digging into the details of the plays. She should look at Kickstarter campaigns for plays that were in her same genre. If she looks at similar genre, then she can see what percentage of her same genre of plays hits their goals. This would help determine realistic fundraising goals, donation request amount and estimated number of backers to expect. Additionally, it would be useful to see where the play and fundraising location was. This would give her an idea of what to expect for her location. New Yorkers might be more apt to donate than someone in Reno. 

### Additional Tables and Graphs to create

#### Country level data
I think it would be interesting to drill down to her specific country to see more details on US play kickstarter data. Having other countrys' results in a US based play might skew the results for Louise's purposes and include irrelevant data. 

#### Backers and Avg Donation Amount
It might be interesting to look at the campaigns with the most backers and examine if there is a correlation between between backers and average donation amount. Maybe determine if it is better to request less from more people or try to ask for bigger numbers from less people.

#### Spotlight
It would also be interesting to determine if campaigns that are spotlighted tend to be more successful. Does paying the extra fees make a difference in the success of her campaign to help determine if the money spent will result in correlating money raised?

#### Year Campaign was Launched
I think that looking at campaign launch date might be relevant. If we could map out the trend over a time period, we could determine if there is an overall decline or increase in donations throughout the years. 
