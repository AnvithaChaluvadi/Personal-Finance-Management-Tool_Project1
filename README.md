#### Project 1: Personal Finance Management Tool
##### Anvitha Chaluvadi, Maria Notarianni, Owura Fosuhene Akosah

# **<ins>Debt-Defying Budget Buddy</ins>**

## Background
Streamlining the budgeting process through automation allows users to swiftly identify their spending patterns, optimize income, and gauge their financial well-being in comparison to the national average.


## What We’re Creating

We are creating a tool that analyzes and visualizes expenses made last year and determines which month, category of transactions he spent more and to track his expenses and to know if he spent right the whole year. Once the user understands how they spent their money last year, they will be better equipped to set goals for the future.

## Prepared the Data

First, we read and clean the CSV file for our analysis. The CSV file contains data on numerous expenses from last year. Use the personal transaction data to complete the following steps:

* Utilize Pandas to read the CSV file into DataFrames, ensuring the conversion of the date to a DateTimeIndex.
* Adjust data types as necessary.
* Remove the extra column 'description.'
* Change the category column to 'unassigned.'

## Performed Quantitative Analysis
We analyzed the data to determine what month or category the user spent more and to know if they spent right the whole year. Specifically, we will do a analysis by calculating the total amount spent for each category and month.

We presented data and graphs for the following code: 

<p align="center"> <img src = Images/MonthExpen.jpg width =45% height 30%=/> </p>
<p align="center"> <img src = Images/LastYearExpen.jpg width =45% height 30%=/></p> 


## Confirming User Satisfaction
 
 We asked the user this questions:
 * Are you satisfied with your spending? (yes/no): No
 * In that case, let's proceed with addressing your need for help with budgeting.

## Summary Dashboard

 We have developed a widget that enables users to delve deeper into their summary table, allowing them to explore specific categories and/or months.

<p align="center">
<img src = Images/WholeSummaryDashboard.gif width =60% height 30%=/>
</p>

## A Month's Expenses From User Input

* Created a user input that asks the question, "Which month would you like to explore further?"
* Filtered the data to include only transactions from the selected month.
* Created a table for the selected month with two columns: category and amount.
* Calculated the total amount across all categories for the chosen month.
* Plotted a bar chart to visualize the amount spent in each category.

<p align="center"> <img src = Images/InputMonthExpen.jpg width =45% height 30%=/></p> 

## What New Monthly Goal?

* Asked user for new monthly budget they would like to expect in parts: 
    * Their Monthly Income
    * Expected Mortgage/Rent Expense
    * Expected Shopping Expense
    * Expected Utilities Expense
    * Expected Food Expense
    * Expected Gas Expense
    * Expected Monthly Savings Goal
  
* Calculated user's monthly budget by the sum of all the user's expenses for new month.

* Function that calculated the impact on savings goal to know if the user is on track to meet the savings goal.

* Plotted and created a function to compare budget and expenses.

<p align="center"> <img src = Images/BudgetExpenses.jpg width =45% height 30%=/></p> 

## Comparison Between User Budget and Average American Budget

* Obtained statistics on the average American monthly budget from multiple websites.
* Calculated the difference between the average American monthly budget and the user's monthly budget.
<p align="center"> <img src = Images/BudgetDifference.jpg width =45% height 30%=/></p> 

* Created a table column displaying the Category, average American monthly budget, and the user's monthly budget input.
* Plotted both on one graph, comparing the average American monthly budget and the user's monthly budget input.

<p align="center"> <img src = Images/AvgAmericanBudget.jpg width =45% height 30%=/></p> 

### <ins>Resources</ins> 
   
[The Ascent - American Households' Average Monthly Expenses: $6,081](https://www.fool.com/the-ascent/research/average-monthly-expenses/#:~:text=Share-,Average%20monthly%20food%20spending%3A%20%24779%20(13%25%20increase),%249%2C343%20over%20the%20full%20year.)

[Bankrate - The Average American Household Budget](https://www.bankrate.com/banking/savings/average-household-budget/#faqs)

[ValuePenguin - Average Household Budget: How Much Does the Typical American Spend?](https://www.valuepenguin.com/average-household-budget#:~:text=We%20spend%20an%20average%20of,monthly%20income%20in%20the%20U.S.)

[RentCafe - Average Rent in the U.S.](https://www.rentcafe.com/average-rent-market-trends/us/)

[J.D. POWER - RentCafe - How Much Do People Spend On Gas Each Month?](https://www.jdpower.com/cars/shopping-guides/how-much-do-people-spend-on-gas-each-month#:~:text=What's%20The%20Average%20Monthly%20Spend,2.24%25%20of%20their%20monthly%20income.)

[Kaggle](www.kaggle.com.)


### <ins>Presentation</ins> 
[Debt-Defying BudgetBuddy Presentation](https://docs.google.com/presentation/d/1qdo4lPtV1kjsNBMZ6L-lPR1GsPMan-R56250XQWZroY/edit?usp=sharing)



