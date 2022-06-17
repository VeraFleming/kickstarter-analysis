# Kickstarting with Excel

## Overview of Project
Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. I needed to perform the analysis which she can use for making her plans. We've been given a Kickstarter sheet where I can get the data. 

<img width="1723" alt="image" src="https://user-images.githubusercontent.com/105990653/174350090-d898beba-0025-4768-96f7-37f305173055.png">

### Purpose

  To help Louie to understand how to budget the fundraising amount in order to get enough pledges and when to start her campaign so she could meet her goals. 
## Analysis and Challenges
  I needed to create two new worksheets with the help of the Kickstarter dataset so that I can analyze the charts for outcomes based on launch date and outcomes based on goals. 
  My biggest challenge was getting the relevant data into the pivot table to analyse outcomes based on launch date so that it would look good and display the correct and readable data.
  My second biggest challenge was to get the right COUNTIFS() formulas which would work for the second worksheet we created to analyse otcomes based on goals. 

### Analysis of Outcomes Based on Launch Date
  First, I would need to add a new column to the current Kickstarter worksheet that would display data with the year that each campaign was launched. Then I need to use the "Year" function to convert the dates from the "Date Created Conversion" column to the new format. After that, I could make a pivot table and input it with information from the new column to filter and arrange the data.
  I used a line chart to illustrate the data based on the pivot table I built so that I can determine when Louie should launch her play's campaign.
  I recommend starting the campaign in May or June according to the chart.
  
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/105990653/174350284-9adcdf1d-f978-45bd-aede-1469fea3642c.png)

### Analysis of Outcomes Based on Goals
  In a new worksheet, I needed categorize projects according to their goal amounts which I broke down in a first column. Then, by filtering on the Kickstarter "outcome" column, the "goal" amount column using the ranges specified for projects, and the "Subcategory" column using "plays" as the criteria, I populated the "Number Successful," "Number Failed," and "Number Canceled" columns.
  The percentage of successful, failed, and cancelled projects for each new row can be determined. For Louie to understand what budget for her campaign would be more successful, a line chart titled "Outcomes Based on Goal" was created, showing the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, and canceled projects on the y-axis.
  
![Outcomes Based on Goals](https://user-images.githubusercontent.com/105990653/174350338-7f9c8a56-8331-4845-9924-2b9d6c5c6422.png)

### Challenges and Difficulties Encountered
  This was my first analytical project where I had to visualize data and tell the story about it. The first difficulties I found for myself is trying to see the whole picture of that dataset we’ve got, but since I started working on it I found more and more interesting information I can analyze. 
  There have also been times when I've been totally baffled and haven't been able to figure out why my data is different from the example. I had to repeatedly watch the video about the COUNTIFS formula that was provided before and I finally figured it out!

## Results

  1. Louie should launch her campaign in May or June, are the two conclusions I can make about the outcomes based on launch date.

  2. What conclusions can you draw about the Goals-based Outcomes?
As it appears like a more fair amount and has more money donated for most of the Play campaigns, I would advise Louie to budget her campaign at roughly $45,000 to $49,000.


