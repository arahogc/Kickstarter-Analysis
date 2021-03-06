# An Analysis of Kickstarter Campaign data 

**Purpose and Overview** 
Analysis on Kickstarter data to uncover trends to help Louise better fund her play's budget of about 10,000 dollars. Within this report, you will find thoughts on challenges, data analysis, and some conclusions drawn from the visualized data. The data can be viewed in its entirety in the Excel spreadsheet labeled "Kickstarter_Challenge." 

This challenge is also to use skills learned that related to Excel, to be able to pull out data from specific subsets, and visualize that data in tables and charts. 

**Challenges and Analysis**

*Analysis:* The data was distilled into two different tables with accompanying graphs. The first table is a pivot table that focused on the success or failure of theater projects based on their launch dates. When looking through the data, it could be seen that the most successful month for theater projects was May, where 111 theater projects succeed, followed closely by June. The worst month to launch a play was December. 

![Outcomes_vs_Launch.png](Resources/Theater_Outcomes_Vs_Launch_Date_Final.png)

The second table is a table that examined the success or failure of plays based on the desired goal amount. There are some intesting trends here. Predicatably, projects that had small goal amounts, less than $9,999, had around a 70% success rate (averaged of the three success rates of 76%, 75%, and 55%). Plays that had goals from $10,000-$14,999 had a 53% **failure** rate. At $15,000-$19,999, the plays had a 50/50 chance of either succeeding or failing. Goal amounts higher than $20,000 were more likely to fail. Surprisingly, plays that had goals between $35,000-$40,000 had a 67% success rate. Anything higher, though, was more likely to fail. 

![Outcomes_vs_Goals.png](Resources/Outcomes_vs_Goals.png) 

*Challenges:* There were a couple of challenges that I faced when doing this project. The first was a simple challenge that is almost too embarressing to admit. When making the pivot table for Outcomes vs Launch date, I had a column labeled "Live." But I didn't want that column and probably spent about thirty minutes trying to figure out how to get rid of that unwanted column. I then noticed that you can filter the columns and thus hide any columns that are not wanted. S0... I learned that always check to see if there are filtes before researching more complex solutions for a simple issue. 

The second challenge came with the conditional formating and debugging portion of the challenge. When formatting cells to have certain colors based on the percentage of goal amount founded. There was a lot of one color over the other. The module explained this is becaue of outliers influencing the conditional formatting and that this would be addressed later. However, it wasn't truly addressed. Within the module, there is a section on outliers and it stated that if outliers are greater than 1.5xIQR, than the outlier can be thrownout. I considered creating a column to determine outliers for the entirety of the Kickstarter data set, but ultimately decided it wasn't not worth my time to do so (But I would do it for the small subset of plays and theater projects as needed). So my conditonal formatting for percentage founded does not have that beautiful gradient of colors. 

**Results** 

Based on the data from the charts and tables above, it is recommended that Louise launch her kickstarter for her play in May. If she cannot launch in May, then either April or June would be fine, since it seems warmer months tend do better than colder months. At all costs, she should avoid starting a kickstarter project in Janruary. Further, it is recommended that she decrease the amount of money as well, just to help increase the chances of successfully raising money. However, if she raised her goal amount to around $15,000 than she would have an equal chance of succeeding or failing, which she could influence by investing in to marketing her kicks starter. It is recommend that she does not raise the money above $15,000 since it is very likely that her project would fail. Even though there is the anomaly of plays with budgets around $35,000 succeeding, it is still less than that of projects with budgets less than $10,000, and also it doesn't seem that necessary for her particular play. 

While the data provided does provide some insight in how Louise should approach her Kickstarter, it still has a lot of limitation. The data provided only focused on amount of money raised for the kickstarter; if it succeed, failed, or was cancelled; and what the dates were when the projects were launched and closed. Other factors that would have been useful to examine would be how much they put into marketing their kickstarter and on what platfroms (e.g. what social media platforms, how many ads were put out there) and how well detailed their kickstarter page was (e.g. did they have pictures and details of what the project was or was it just a brief description?). Knowing these kind of factors and how they related to the success or failure of a project would be useful for someone like Louise. 

Other graphs and tables that could have been created include creating a table of success and failed percentage rates for theater projects based on the month, and a table and chart that had tighter ranges of money for goals (e.g. $10,000 to $12,000 vs $10,000 to $14,999).

In conclusion, launching the kickstarter in May and decreasing the amount of money needed will help improve the chances of success for Louise's play. 
