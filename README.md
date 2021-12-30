# Excel Challenge

## Details About the Challenge
This assignment was designed to challenge me to modify and analyze the data of 4,000 past Kickstarter projects and attempt to uncover some market trends found within the [Kickstarter Excel file](/StarterBook.xlsx).

## Instructions
1. Use conditional formatting to fill each cell in the state column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live.
2. Create a new column O called Percent Funded that uses a formula to uncover how much money a campaign made to reach its initial goal.
   - Use conditional formatting to fill each cell in the Percent Funded column using a three-color scale. The scale should start at 0 and be a dark shade of red, transitioning to green at 100, and blue at 200.
3. Create a new column P called Average Donation that uses a formula to uncover how much each backer for the project paid on average.
4. Create two new columns, one called Category at Q and another called Sub-Category at R, which use formulas to split the Category and Sub-Category column into two parts.
5. Create a new sheet with a pivot table that will analyze your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.
   - Create a stacked column pivot chart that can be filtered by country based on the table you have created.
6. Create a new sheet with a pivot table that will analyze your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.
   - Create a stacked column pivot chart that can be filtered by country and parent-category based on the table you have created.
7. Create a new column named Date Created Conversion that will use a formula to convert the data contained within launched_at into Excel's date format.
   - Create a new column named Date Ended Conversion that will use this same formula to convert the data contained within deadline into Excel's date format.
8. Create a new sheet with a pivot table with a column of state, rows of Date Created Conversion, values based on the count of state, and filters based on parent category and Years.
   - Now create a pivot chart line graph that visualizes this new table.
9. Create a report in Microsoft Word and answer the following questions.
   - Given the provided data, what are three conclusions we can draw about Kickstarter campaigns?
     - The category “theater” with the sub-category “plays” are the most common as well as the most successful Kickstarter campaigns overall.
     - The late spring to summer months (May, June, and July) are the most popular time to create a Kickstarter campaign. 
     - Journalism was the least popular Kickstarter campaign and also the only category in which all projects were canceled.
   - What are some limitations of this dataset?
     - There’s no follow-up data: although successfully funded, was the product actually created as promised for the general public to use/purchase?
     - One theory I have as to why the Kickstarter campaigns are most popular in the summer months is that it could be in part due to students being out of school. We don’t have the ages of the creators of these Kickstarter campaigns, so we need more information.
     - I would like to see updated information for years 2019 to the present to see how the global shutdown due to COVID-19 has affected this program.
     - According to the Kickstarter website, there have been 208,284 successfully funded projects (Kickstarter, 2021). This StarterBook sample only has 4114 combined successful, live, canceled, and failed Kickstarter campaigns, so it’s not 100% accurate.
   - What are some other possible tables and/or graphs that we could create?
     - Other tables and graphs we could use would include a pie chart to show the percentage of successful, failed, canceled and live Kickstarter campaigns or a table with the percent funded and the categories to see which categories had the most funding.

## BONUS
1. Create a new sheet with 8 columns.
   - ![image](https://user-images.githubusercontent.com/88349512/147736894-187b42aa-ca6f-4800-a734-14aa70c94e1f.png)
2. In the Goal column, create 12 rows with the following headers:
   - ![image](https://user-images.githubusercontent.com/88349512/147736919-d6ea89d1-d09e-4153-a09c-d3359fa9480b.png)
3. Using the COUNTIFS() formula, count how many successful, failed, and canceled projects were created with goals within the ranges listed above. Populate the Number Successful, Number Failed, and Number Canceled columns with this data.
4. Add up each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column. Then, using a mathematical formula, find the percentage of projects that were successful, failed, or canceled per goal range.
5. Create a line chart that graphs the relationship between a goal's amount and its chances at success, failure, or cancellation.
6. Create a new worksheet in your workbook, and create a column each for the number of backers of successful campaigns and unsuccessful campaigns.
7. Use Excel to evaluate the following for successful campaigns, and then for unsuccessful campaigns:
   - The mean number of backers.
   - The median number of backers.
   - The minimum number of backers.
   - The maximum number of backers.
   - The variance of the number of backers.
   - The standard deviation of the number of backers.
8. Use your data to determine whether the mean or the median summarizes the data more meaningfully.
9. Use your data to determine if there is more variability with successful or unsuccessful campaigns. Does this make sense? Why or why not?
