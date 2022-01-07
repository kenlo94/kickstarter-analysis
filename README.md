# Kickstarting with Excel

## Overview of Project

Use the Kickstarter data to create two new analyses: outcomes based on goals and outcomes based on launch date. There are 3 deliverables that need to be submitted: 1 chart for each of the analyses (2 total) and a written analysis of the results. The first chart will be a pivot chart created from manipulating/analyzing the existing data from the Kickstarter excel file. The first chart consists of Theater outcomes vs Launch date. With this chart, we were able to determine how successful (successful, failed, canceled) a campaign was based off of the month that they were launched in. The second chart will be a line chart created after you have created a new sheet within the excel file and using the COUNTIFS() function. This second chart consists of Play outcomes vs their Goal amount (in dollars). With this chart, we were able to determine the percentages of campaigns that were successful, failed, or canceled based on the goal ranges and if they met their goal amount. 

### Purpose

The purpose of this challenge is to continue to develop and challenge our excel skills that we have developed over the first two classes. For the first deliverable, this includes creating new columns, sheets, and pivot tables, filtering the pivot table, and creating a chart from that pivot table. For the second deliverable, this includes changing the format of data in a column, using a new function, and visualizing percentages using a chart.

## Analysis and Challenges

I performed by analysis by simply following the directions. For the first deliverable, I created a new sheet for my pivot table, filtered the data, sorted the data, then created a chart from the data in the pivot table. For the second deliverable, I created a new sheet with new rows and columns, used a new COUNTIFS() function, filtered the existing data, then created a chart from the data in the new sheet. A challenge I ran into was learning how to use the new COUNTIFS() function. This was the first time I had used this function and I was unsure what criteria to input into the argument. Once I researched how this function operates it was easier to understand. However, I was still making errors on my notation so I kept having to go back and forth to edit my criteria so that I would get the correct result. Another challenge I ran into was that my 2nd chart did not match up with the correct chart online. I found out that I forgot to filter the subcategory column by "plays" as the critera. Once I was able to fix this issue, my chart matched up with the correct chart online.

### Analysis of Outcomes Based on Launch Date

- What are two conclusions you can draw about the Outcomes based on Launch Date?

If a campaign is launched in the Summer months (May, June, July) then they are more likely to succeed since the count of successful campaigns is higher during that time period. Another conclusion that can be drawn is that canceled campaigns are low and steady all year round at or below 7 counts.

### Analysis of Outcomes Based on Goals

- What can you conclude about the Outcomes based on Goals?

Generally speaking, the lower the goal amount, the higher the success rate. Although there are some instances where campaigns are just as successful in the 35k to 45k range. Looking at the chart created, it also seems that both curves for percentage successful and percentage failed are mirror images of one another. Also, none of these campaigns were canceled, which was quite surpising to see.

## Results

- What are some limitations of this dataset?

This dataset has a lot of data at 4,115 rows but there is not much information. This dataset mainly tells you if a campaign was successful, if they failed, or if they were canceled. There are about 40 subcategories but only 9 parent categories so I feel that the data could be more helpful if it was more expansive. However, for Louise's case, I believe the date served its purpose.

- What are some other possible tables and/or graphs that we could create?

We could create graphs using different filters for the parent category and subcategory. Instead of looking at just "Theatre" and "plays", maybe we could take a look at "Games" and "Video games". We could also take a look at the percentage funded and the average donation to see if they have any impact on the outcome of a campaign(successful, failed, canceled).  
