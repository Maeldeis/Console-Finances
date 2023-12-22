# Console-Finances

Week 4 challenge
My task is to write JavaScript code that analyzes the records to calculate each of the following:

* The total number of months included in the dataset.

* The net total amount of Profit/Losses over the entire period.

* The average of the **changes** in Profit/Losses over the entire period.
  * Track what the total change in Profit/Losses are from month to month and then find the average.
  * (`Total/(Number of months - 1)`)

* The greatest increase in Profit/Losses (date and difference in the amounts) over the entire period.

* The greatest decrease in Profit/Losses (date and difference in the amounts) over the entire period.

Overall Profits or Losses:

Go through each month's data, adding up profits and losses.
After the loop, check if the total is positive (profit) or negative (loss).

Average Change in Profits:

Begin with a total change set to zero.
Go through each month (excluding the first) and see how profits change.
Add up all the changes and calculate the average.

Biggest Increase and Decrease:

Set aside dates and amounts for the biggest increase and decrease.
Go through each month (excluding the first) and find changes.
If a change is bigger than what we've seen before, update our records.
Finally, share the dates and amounts for the biggest increase and decrease.
