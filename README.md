# Unit 4 Challenge: Console Finances

## Overview

The console finances analysis script provides insights into financial data, including:

- **Total Months**: Calculates the total number of months included in the dataset.
- **Total Profit**: Computes the sum of all profits/losses over the entire period.
- **Average Change**: Calculates the average change in profits/losses between consecutive months.
- **Greatest Increase**: Identifies the month with the highest increase in profits and the corresponding amount.
- **Greatest Decrease**: Identifies the month with the largest decrease in profits and the corresponding amount.

The code processes financial data represented as a JavaScript array of arrays, with each inner array containing a month-year string and a corresponding profit/loss value. Metrics are calculated using appropriate logic within separate sections of the code, and results are displayed in the console using `console.log()` statements.
Please see the deployed page here: https://catbeckett.github.io/Console-Finances/

## Usage

To use this code:

1. Ensure the `finances` array contains the desired financial data.
2. Run the script in a JavaScript environment (e.g., a web browser console or a Node.js environment).
3. View the console output to see the calculated financial metrics.

## Example Output

The code in the browser with the resulting analysis looks similar to the following:

  ```text
  Financial Analysis 
  ----------------
  Total Months: 86
  Total: $38382578
  Average Change: -2315.12
  Greatest Increase in Profits/Losses: Feb-2012 ($1926159)
  Greatest Decrease in Profits/Losses: Sep-2013 ($-2196167)
  ```

  ## Screenshot
![Deloyed-Console-Finance Screenshot](/Assets/Deloyed-Console-Finance%20Screenshot.png)