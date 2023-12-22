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

I possess a dataset containing monthly financial information, specifying the profit or loss for each period. My objective is to extract insights from this data utilizing for loops and if statements.

Calculating Net Profits or Losses:

Initialize a variable to accumulate the total profit or loss.
Employ a for loop to iterate through each month's data.
Inside the loop, add the current month's profit to the total.
Post-loop, output the total; a positive value indicates a net profit, while a negative value denotes a net loss.
Determining Average Change in Profits:

Initialize a variable to store the total change in profits.
Initiate a for loop, starting from the second month.
Inside the loop, obtain the current and previous month's profits.
Calculate the profit change and add it to the total.
After the loop, compute the average change by dividing the total change by the number of periods.
Output the average change in profits.
Identifying Greatest Increase and Decrease in Profits:

Initialize variables for the date and amount of the greatest increase and decrease.
Commence a for loop, starting from the second month.
Inside the loop, compute the change in profits between the current and previous months.
If the change is greater than the current greatest increase, update the variables with the current data.
If the change is less than the current greatest decrease, update the variables accordingly.
Post-loop, output the date and amount of the greatest increase and decrease in profits.
