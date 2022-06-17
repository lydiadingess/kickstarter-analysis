# Kickstarting with Excel

## Overview of Project: 
This project was prepared to analyze the outcomes of different Kickstarter projects

### Purpose: 
Our purpose was to compare and analyze outcomes of theater and play Kickstarters to understand what was successful and where needs improvement. We used the Kickstarter data to conceptualize campaign outcomes based on their launch date and their fundraising goals. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date: 
Based off launch data, we can conclude that theater Kickstarters perform better in the spring through summer season. According to the graph, we see a drastic increase of successful theater kickstarts from April to May, then a decline from September through December. 
![Theater_outcomes_vs_launch](C:\Users\lydia\OneDrive\Documents\resources\Theater_outcomes_vs_launch.png)

### Analysis of Outcomes Based on Goals: 
In this analysis we breakdown the number of successful and failed plays against their fundraising goals. We then compare the percentage of success and failed in relation to the cost of each production. We can see that the lower the cost of each campaign the higher the success rate. Once the fundraising goal increases ofver $15,000 the chance of success drops to about 50%. However, a few outliers to note. Projects with larger goals saw better success rates when there were fewer projects in that goal range. 
![Outcomes_vs_Goals]("C:\Users\lydia\OneDrive\Documents\resources\Outcomes_vs_Goals.png")

### Challenges and Difficulties Encountered: 
The main challenge I encountered was during the "outcomes based on goals" analysis. Using the =COUNTIFS() function required some trial and error before receiving accurate results. After review the course material, I was able to find the correct function, =COUNTIFS(Kickstarter!D:D,">=1000",Kickstarter!F:F,"successful",Kickstarter!D:D,"<=4999",Kickstarter!R:R,"plays")


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? 
1. Theater Kickstarter perform better in the spring season beginning in April
2. Around the holiday season, people are not attending theater performances. This would be why we see a decline in successful theater Kickstarter beginning in October. 

- What can you conclude about the Outcomes based on Goals?
1. Plays with goals under $4999 had the highest have the greatest chance of success.
2. There should be a limited number of plays with higher monetary goals, to enable more successful plays. 

- What are some limitations of this dataset?
1. In the outcomes based on goals we do not limit the dollar amount to a specific currency/ country. 
2. We do not take into account any other factors such as: the type of play or the topic that was being covered.

- What are some other possible tables and/or graphs that we could create?
1. View the average donation against the success or failure of the play 
2. Comparing the success plays in realtion to the country that they were preformed in, viewing the different success/failure across the world

