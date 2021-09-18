# Excel: Kickstart My Chart

## Background

Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.

Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success. For this week's homework, you will organize and analyze a database of 4,000 past projects in order to uncover any hidden trends.

## Accomplishments

[Kickstart_Excel](StarterBook.xlsx)
1. Using conditional formatting, each cell in the **state** column is filled with a different color depending on whether the associated campaign was successful, failed or canceled or is currently live.

2. Created a new column called Percent Funded that used formula to uncover how much money a campaign made to reach it's initial goal. ((Pledged/Goal)*100)

![Conditional Formatting](/images/Outcome.jpg)

3. Pivot Table - Analyzing initial worksheet to count the outcome of campaigns per **category** further creating a stacked pivot chart that can be filtered by country

![Pivot Table 1](/images/Category.jpg)

4. Pivot Table - Analyzing initial worksheet to count the outcome of campaigns per **sub-category** further creating a stacked pivot chart that can be filtered by country and parent-category

![Pivot Table 2](/images/Sub_category.jpg)

5. Created a new column named Date Created Conversion and Date Ended Conversion
Pivot Table - Analyzed data based on count of outcomes based on months over the years further creating a pivot chart that visualizes the table.

![Pivot Table 3](/images/Deadline.jpg)

### Bonus!

6. Created a new sheet with 8 columns and 12 rows in the **Goal** header.
  Using the COUNTIFS() function, computed number of successful, failed and canceled campaigns for their respective goal condition. Additionally, populated **Total Projects**   and found the percentage of projects per goal condition.
  Lastly, created a line chart that graphs the relation between a goal amount and it's outcome.

![Goal Conditions v/s Outcome](/images/Bonus.jpg)

### Bonus Statistical Analysis!

7. Created a new sheet with number of backers of succesful and failed campaigns and evaluated their stats respectively.

![Backers](/images/Bonus_Stats.jpg)

## Conclusions

[Conclusion](Kickstart_Chart.docx)












