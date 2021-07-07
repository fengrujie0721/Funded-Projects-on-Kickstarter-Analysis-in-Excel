# Funded Projects on Kickstarter Analysis in Excel
Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.
Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success. An analyze of a database of 4,000 past projects was done in order to uncover any hidden trends.


![image](https://user-images.githubusercontent.com/79819331/119204757-4ad68200-ba64-11eb-8da7-ed4a6e3822d3.png)

Use conditional formatting to fill each cell in the state column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live. Create a new column O called Percent Funded that uses a formula to uncover how much money a campaign made to reach its initial goal. Use conditional formatting to fill each cell in the Percent Funded column using a three-color scale. The scale should start at 0 and be a dark shade of red, transitioning to green at 100, and blue at 200.




![image](https://user-images.githubusercontent.com/79819331/119153579-5f445b80-ba1f-11eb-9666-a405f082ff63.png)

Create a new sheet with a pivot table that will analyze initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category. 


![image](https://user-images.githubusercontent.com/79819331/119153933-b0ece600-ba1f-11eb-99b0-5f9141670ab9.png)


Create a stacked column pivot chart that can be filtered by country based on the table you have created.




![image](https://user-images.githubusercontent.com/79819331/119153987-be09d500-ba1f-11eb-8a7f-73de245ba73f.png)

Create a new sheet with a pivot table that will analyze your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category. Create a stacked column pivot chart that can be filtered by country and parent-category based on the table have been created.


![image](https://user-images.githubusercontent.com/79819331/119154070-d24dd200-ba1f-11eb-8b0e-b07b58ed473d.png)

The dates stored within the deadline and launched_at columns use Unix timestamps. Fortunately, there is a formula that can be used to convert these timestamps to a normal date. Create a new column named Date Created Conversion that will use this formula to convert the data contained within launched_at into Excel's date format. Create a new column named Date Ended Conversion that will use this formula to convert the data contained within deadline into Excel's date format. Create a new sheet with a pivot table with a column of state, rows of Date Created Conversion, values based on the count of state, and filters based on parent category and Years.

![image](https://user-images.githubusercontent.com/79819331/119154114-dc6fd080-ba1f-11eb-9fff-b3633a4b3665.png)


Create a new sheet with 8 columns:

Goal
Number Successful
Number Failed
Number Canceled
Total Projects
Percentage Successful
Percentage Failed
Percentage Canceled

In the Goal column, create 12 rows with the following headers:

Less than 1000
1000 to 4999
5000 to 9999
10000 to 14999
15000 to 19999
20000 to 24999
25000 to 29999
30000 to 34999
35000 to 39999
40000 to 44999
45000 to 49999
Greater than or equal to 50000

Using the COUNTIFS() formula, count how many successful, failed, and canceled projects were created with goals within the ranges listed above. Populate the Number Successful, Number Failed, and Number Canceled columns with this data. Add up each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column. Then, using a mathematical formula, find the percentage of projects that were successful, failed, or canceled per goal range.







![image](https://user-images.githubusercontent.com/79819331/119154634-5738eb80-ba20-11eb-82b3-367ab285e2c1.png)


Create a line chart that graphs the relationship between a goal's amount and its chances at success, failure, or cancellation.



Summary:
1.	Three conclusions:
A.	Category Theater has the largest number of successful cases, which is 839. 
B.	Sub-Category Plays has the largest number of successful cases, which is 694.
C.	May is the month that has the most successful cases.
2.	Limitations:
There are all together 300,000 cases. The sample here is only 4,000. Only a third can get positive outcome. In this sample, the success rate is 2185/4114=0.53. Therefore, the sample showed higher success rate than the actual one.
3.	Other possible tables/graphs:
Pivot table that counts how many campaigns were successful, failed, canceled, or are currently live per country, per goal.

