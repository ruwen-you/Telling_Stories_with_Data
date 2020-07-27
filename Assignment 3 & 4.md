# Assignment 3&4 - Critique by Design

## Original Data Visualization - Where New Cases are decreasing Most (Metro Areas)

![Original Data Visualization](https://github.com/ruwen-you/Telling_Stories_with_Data/blob/master/Original%20Data%20Vis.png)

Source: New York Times database of reports from state and local health agencies and hospitals

Original Article: [Monitoring the Coronavirus Outbreak in Metro Areas Across the U.S.. The New York Times.](https://www.nytimes.com/interactive/2020/04/23/upshot/five-ways-to-monitor-coronavirus-outbreak-us.html)

## Critique

We are living in the pandamic now. There is so much news and data around COVID-19. I picked the recent one from The New York Times.

It is a table with a lot of numbers and some colors to compare the number of the decreasing new cases and decreasing new deaths of metro or micro areas in the last two weeks. The headers of the tables and the columns are very clear to guide the audience to understand the meaning of the columns. 

I like their use of the colors in this table. They use colors in two places. First is change per 100k. They use gradient color to represent the high to the low. The second is the row - New York City area. They use dark grey to help the audience focus on it and compare with other areas, which makes it easy to show New York City area’s decreasing new cases and deaths are not many compared to others.

* However, it’s hard for the audience to understand the quantity relationship by reading so many numbers. 
* It’s hard to get how much difference between the different numbers. 
* Although it has 6 scales, the table only uses two close scales. As a result, -164 and -1.8 look like in the same level. The scale can be in higher-level granularity to show the difference. 
* Besides, I think it’s also necessary to provide the information of population difference to help the audience understand why areas with more decreasing cases may not be the best news relative to the population. 
* Last but not least, it’s hard to use numbers to compare the two columns - A week ago and now. We can find a more intuitive way to get the decreasing trend for each area. In summary, I will use more graphs to show the relationship of the quantity instead of numbers.

## Wireframing of the Redesign
![Wireframing](https://github.com/ruwen-you/Telling_Stories_with_Data/blob/master/Redesign%201.png)
![Wireframing - Hover](https://github.com/ruwen-you/Telling_Stories_with_Data/blob/master/Redesign%202.png)

I used a bar chart to redesign the data visualization. Here are the changes I made:
* Only use four colors for the scale. No need to have colors for the scale between (-992) - (-192). But I use colors to make difference between (-200)-(-100) and (-100)-0, which is in a higher granularity to show the difference.
* I use bar chart instead of table to show the number difference in quatity.
* I use pink to highlight New York Area, making it more obvious to see it is the only one growing.
* I use a hover feature to show the change trend during the last week so that the audience can easily compare before and after.

## Testing and Feedback
## Final Solution
## Summary
