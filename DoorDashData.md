# Data Dash
<br><br>
## A Deep Dive into DoorDash Data
<br><br>
I'm a sucker for a good promo. Every week, I get a notification on my phone from DoorDash and other delivery apps with their latest offers. This week, after giving into temptation and placing an order, I assured myself that I'm not the only one who can't pass up a good deal. In an attempt to validate my most recent purchase, I wanted to look at the data to see if other people do the same. How many people are drawn to food delivery apps by marketing campaigns? What encourages some people to order more than others?
<br><br>
With the help of a dataset I found online, I was able to answer these questions and more to curb my curious appetite. After importing over 2,000 rows of data into Excel, I learned that:
<br><br>
-$1.24 million was spent by customers between 2014-2016
<br>
-67.7% of the spend variance can be explained by income levels
<br>
-An average of 7.5% of customers placed an order following each marketing campaign
<br><br>
## Data on Demand
<br><br>
This data comes from a Brazilian equivalent of DoorDash called iFood. It was a use case for an interview process and was adjusted by [Avery Smith](https://www.linkedin.com/in/averyjsmith?miniProfileUrn=urn%3Ali%3Afs_miniProfile%3AACoAABCG_r4BYd2__W11z2ermYRU4r7aj6H-zug&lipi=urn%3Ali%3Apage%3Ad_flagship3_pulse_read%3BfUnb6pZCSdWLHY%2F4zHOluw%3D%3D) for educational purposes. You can find the data set [here](https://www.kaggle.com/datasets/jackdaoud/marketing-data).
<br><br>
Based on what I was trying to find out, I deemed these columns relevant for analysis: Customer ID, Income, Amount Total Spent, Accepted Campaign 1, Accepted Campaign 2, Accepted Campaign 3, Accepted Campaign 4, Accepted Campaign 5, Accepted Campaign 6, and Days as a Customer. Each row in the data represents a unique customer.
<br><br>
## All You Can Eat Insights
<br><br>
Using various aggregate functions in Excel, I was able to learn more about how customers use iFood, as shown in the Summary Table. The total amount purchased by 2,205 unique customers from 2014-2016 was $1.24 million, with each customer averaging at $562.76.
<br><br>
<img src="images/Graph1.png?raw=true"/>
<br><br>
While the average amount spent per customer from 2014-2016 is $562.76, we can see from the Amount Total Histogram that over half of the customers spent between $4 and $418.50 within this time frame. Based on this information, the company may benefit from marketing toward those who spend lower amounts in order to increase the amount of higher spenders in future campaigns.
<br><br>
<img src="images/Graph2.png?raw=true"/>
<br><br>
After learning how much people spent on iFood services, I was curious to know why some people spent more on food delivery than others. Looking at the Income vs Total Spent scatter plot, we can see that there is a correlation between the customer's income and how much they spent. The R² value tells us that the income level explains almost 70% of variance in the amount spent. With this information, the marketing team can target customers with higher income in marketing campaigns.
<br>
After considering who may be more inclined to spend money following a marketing campaign, I wanted to know how many customers actually accepted marketing campaigns.
<br><br>
<img src="images/Graph3.png?raw=true"/>
<br><br>
Looking at the Campaign Orders graph, we can see how many people purchased from iFood following each of six total marketing campaigns between 2014-2016, with an average of 7.5% of customers responding to each marketing campaign.
<br>
The graph shows a wide range of campaign success, with Campaign Two being the least successful at 30 customer purchases, and the most recent campaign, Campaign Six, having the most success with 333 customers acting on this campaign. From this, the marketing team can tailor future campaigns to be more similar in marketing style and value to Campaign Six compared to that of Campaign Two.
<br><br>
<img src="images/Graph3.png?raw=true"/>
<br><br>
## Bringing Home the Bacon
<br><br>
The proof is in the pudding:
<br><br>
-Customers spend a total of $1.24 million, with more than half of customers spending less than $418. <br>
-Income can explain almost 70% of variance in the amount of customers spent. <br>
-On average, 7.5% of customers placed an order in response to a marketing campaign, with over 15% of customers acting on the most recent campaign.
<br><br>
## Feast On
<br><br>
Thank you for checking out my DoorDash project. I appreciate any feedback or questions. Connect with me on [LinkedIn](https://www.linkedin.com/in/calliecowart/?lipi=urn%3Ali%3Apage%3Ad_flagship3_pulse_read%3BfUnb6pZCSdWLHY%2F4zHOluw%3D%3D), and be on the lookout for future projects from me!
