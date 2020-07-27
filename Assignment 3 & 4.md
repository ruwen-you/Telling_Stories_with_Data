# Assignment 3&4 - Critique by Design

## Original Data Visualization - Where New Cases are decreasing Most (Metro Areas)

![Original Data Visualization](https://github.com/ruwen-you/Telling_Stories_with_Data/blob/master/Original%20Data%20Vis.png)

Source: New York Times database of reports from state and local health agencies and hospitals

Original Article: [Monitoring the Coronavirus Outbreak in Metro Areas Across the U.S.. The New York Times.](https://www.nytimes.com/interactive/2020/04/23/upshot/five-ways-to-monitor-coronavirus-outbreak-us.html)

The table shows the change of COVID-19 cases in decreasing metro areas. I chose this visualization because COVID-19 influences my life and learning a lot. There is a lot of data on website now. But I want to know what the public really want to know. Numbers? Trends? Locations? Or only the conclusion? Before I found this visualization, I always think table is much less powerful than other formats. But I actually got clear conclusion when I saw it. I learnt from this data vis first, then started to think about how to redesign it.

## Design Process
Step 1: Understand the pros and cons of the original visualization
Step 2: Wireframing at the lowest cost to do the redesign
Step 3: Testing the wireframing to get feedback
Step 4: Iteration based on the feedback

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
I did testing with 2 students and got the following feedback:
* It's wierd to see all of the bars are under the axis, which is different from the common bar charts.
* Bars already show the quantity difference, colors may be extraneous for delivering the information.
* The pink bar of New York City area is too small, hard to find it.
* The header is decrease. Decrease -100 means increase, which is not what it intended to mean.
* The hover feature with a box to show the trend is confusing. Didn't get what it means. Didn't notice there is a difference between the unit of measurement.

Iteration:
* I realized bar chart is not a good choice to show the trend. Adding a line chart to each bar chart is more confusing. So I decided to change it to line chart to mainly show the trend of the change.
* The participants didn't care much about the specific numbers, they only want to know the comparison.
* There is no need to use colors if I already used graphs to show the comparison.
* No need to indicate decrease or increase. The audience will directly know it by comparing the graphs.

Then I got the following solution.

## Final Solution

<div class="flourish-embed flourish-slope" data-src="visualisation/3298224" data-url="https://flo.uri.sh/visualisation/3298224/embed"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

<div class="flourish-embed flourish-slope" data-src="visualisation/3303188" data-url="https://flo.uri.sh/visualisation/3303188/embed"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
