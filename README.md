# Exercise 3

**Disclaimer: The data presented in this exercise is purely fictive and crafted for educational purposes only.**

1. Navigate to the Galactic Inn Stock Price sheet within the spreadsheet.

2. Add a new column called "Open vs Close" to see how much the opening and closing prices differ. Now, subtract the Open column value from the Close column value, starting from the second row. Answer: =E2-B2 = -8.51

3. Duplicate the cell references from the second row of the Open vs Close column down to row 125.

4. Highlight all data within the Open vs Close column. Answer: =ROW(H1)<=125

5. What was the mean discrepancy between the opening and closing prices?

**Answer: =AVERAGE(B2:B125-E2:E125) = -0.29**
