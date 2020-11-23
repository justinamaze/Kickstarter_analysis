# Kickstartering with Excel

## Overview of the project
Thoughout this project I will be creating an analysis based on the funding and and launch dates of the different campaigns. I will create a chart with the outcome of the Launch dates and outcome of the Based Goal of the campaigns. To help visualize the outcomes I will be providing line graphs of the charts

### Purpose
The purpose of this project is to utilize the Kickstarter dataset to provide the visual Theater outcomes based on Launch date and Outcomes Based on the Goal. 

## Analysis and Challenges
Created two analysis which are the Outcomes based on the Launch Date and Outcomes based on Goals. I used the data from the Kickstarter file to format my data. Once all the data was properly logged in, I then created Line charts so I can visualize the relationships in the charts.

### Analysis of Outcomes based on Launch Date
For the Theater Outcomes Based on the Launch date I used my Starterbook file and renamed it the Kickstarter Challenge. I then created a new folder called resources so I can show results of the graphs of the outcomes.  With the Kickstarter file I created a new column labeled ‘Years. I extracted the data that was in the ‘Date Created Conversion’ and put it in the years column while using the Years() function. I then created a pivot table from my Kickstarter sheet and placed the pivot table in on a new sheet. I renamed the sheet “Theater Outcomes by Launch Date.” I added the “patent category” and the “Years” category from the pivot table to the pivot table. I placed the ‘outcomes’ under the columns, the ‘The date created conversion’ in the Rows, and the ‘Count of Outcomes’ in the values field. I then filtered the column labels so they can only show Successful, Failed, and Canceled. I then grouped the ‘Row Labels’ so it can show the months of the year. Then I filtered the ‘Parent Category’ so it can only show the data for the theater. I sorted the campaign outcomes in descending order so it can show successful first. I then created a Line graph from the pivot table so I can see the data between the outcomes and launch month. I also added the title to the line chart Theater_Outcomes_vs_Launch.png

![Resources/Theater_Outcomes_vs_launch](/Resources/Theater_Outcomes_vs_launch.png)

### Analysis of Outcomes based on Goals
For the Outcomes Based on Goals I created a new sheet and labeled it ‘Outcomes based on Goals’. In the new sheet I created columns for the data of the Goal, Number Successful, Number Failed, Number Cancelled, Total Projects, Percentage Successful, Percentage Failed, and Percentage Canceled. In the Goal column I put a range of dollar amount that the other rows can abide by. In the other rows for Number successful, Number failed, and Number Cancelled I used the Countifs function to determine the outcomes from the Goal row. I then used the Sum function to determine the data in the Total Projects row for the Number so successful, failed, and cancelled projects. I then created a Line chart with the Outcomes Based on Goal title so I can see the results. On the x-axis I can see the goal-amount ranges and the percentage of successful, failed, or cancelled projects on the Y-axis. Finally, I saved my chart as Outcomes_vs_Goals.png in my resources folder. 

![Resources/Outcomes_vs_Goals](/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
I came across severall challenges throughout this project. The most memeorable would be using the countifs function. The fucnction requires a long list of formulas and with one mistake or error in that formula your entire answer will be wrong. I overcame this challenge by being patient and watching the Hint video so I can see how it's done visually. 

## Results
For the Theater Outcomes by Launch Date sheet i've concluded that the successful theater outcomes area took place in the spring and summer for the months of May to August. What I can also conclude is that May is month that had the most succefull theater outcomes and the most failed outcomes as well. 
For the Outcomes based on goals sheet i've concluded that the lowest goal has the highest success percentage and vice versa for the highest goal with the lowest success percentage. I've also concluded that most projects were done in between the 1000 to 4999 range. 

- Limitations
I'd say one limitation of this data sheet is in the Theater outcomes by launch date sheet. In the month of October there weren't any cancellations and it shows on the graph. But on the graph the lines stop which brings more attention to the graph. How does an indiviual who's looking at the graph and chart know that the number is supposed to be zero in that blank?

- Tables/Graphs
A suggested pivot table and chart that could be created could be a sheet with the successful groups with the backers count. So people can see what groups received extra funding and who had the most on the back-end during their funding.
