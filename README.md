# An Analysis of Kickstarter Campaigns
## Overview of Project
This project was designed to assist Louise, an aspiring playright, to help her fund her new play, Fever. Crowdfunding data for over 4,000 productions was included in the initial dataset. Productions were not solely limited to theater kickstarters, so the data was filtered to focus primarily on plays for this analysis. The initial dataset included a number of variables for each production, including: the name, a short "blurb" or description of the project, the goal and actual amounts of money pledged, the outcome (whether the production was canceled, failed, live, or successful), the location (based on country), the currency of the money pledged, whether the prodcution was a staff pick, the number of backers, whether the production was in the "spotlight," the category and subcategory, and the date the production was launched. Not all of these variables were utilized in our analysis.

## Analysis and Challenges
Crowdfunding data was organized, sorted, and analyzed in Mircrosoft Excel to help Louise determine if there are any specific factors that can influence the funding she receives for her play, in order to provide with the best opportunities for success. The data was presented in a variety of tables in charts for more accessible viewing. Measures of central tendancy, including the median, mean, range, and standard deviation were calculated for a number of variables. In addition, quartiles and outliers were also calculated and charted in order to most accurately represent the data.

Challenges that were encountered during this data analysis were mainly related to intricate data analysis. When trying to determine the number of successful, failed, and canceled plays based on goal, I had some trouble creating the correct formulas to correctly filter and count the correct data. Using the COUNTIFS formula required significant trial and error due to the level of specificity that was required to calculate each number correctly. In order to work through this challenge, I did additional research on how to use this formula, and implemented the direction I was provided. This extra step provided me with the necessary guidance I needed to correctly utilize this formula and extract the correct data.

Another challenge I had was when creating a few of the pivot tables to showcase the data based on certain categories. Correctly displaying the specified categories of data in a presentable fashion also took a couple of tries, as my experience with pivot tables in limited. After spending some time experimenting with a number of different combinations while going through the lessons again, I was able to work through this challenge.

See the following images below for some of the analyzed data and corresponding graphs:

![Outcomes based on Months](https://github.com/marikachrisanthopoulos/Kickstarter-Analysis/blob/main/Months.png)

![Outcomes based on Months Graph](https://github.com/marikachrisanthopoulos/Kickstarter-Analysis/blob/main/Theater_Outcomes_vs_Launch.png)

![Outcomes based on Goals](https://github.com/marikachrisanthopoulos/Kickstarter-Analysis/blob/main/Percentage.png)

![Outcomes based on Goals Graph](https://github.com/marikachrisanthopoulos/Kickstarter-Analysis/blob/main/Outcomes_vs_Goals.png)

![Statistics](https://github.com/marikachrisanthopoulos/Kickstarter-Analysis/blob/main/Statistics.png)



## Results
Data analysis in the Theater Outcomes by Launch Date worksheet reveals that more plays are launched in the spring and early summer than in the other seasons. In addition, productions launched in the spring and early summer months generally have higher success rates than those launched in the winter, fall, or later summer months. The number of successful productions during the summer months is much higher relative to the number of failed productions: the number of successful productions in comparison to failed productions in the fall months are almost the same.

The Outcomes based on Goals worksheet reveals that a higher percentage of plays are successful if they have a lower goal in comparison to plays with higher goals. For example, over 70% of plays with goals of less than $5,000 were successful: only 20% of plays with goals between $25,000 and $30,000 were successful. In additon, most plays were within the range of a $10,000 goal (86%).

One limitation of the dataset is that productions are only separated by country: considering we were only focused on plays in the United States, having the ability to filter by state could have been useful, if we were aware of where Louise was trying to create and fund this production. Data about who was creating the production could have been helpful as well: whether it was an individual or group, and whether it was their first production or not. In addition, data about the type of advertising each production received would have also improved our analysis. One additional table/graph that could have been created include the number of backers in comparison to the average donation and total amount of money pledged. Another includes comparing the deadline, launch date, and outcome.
