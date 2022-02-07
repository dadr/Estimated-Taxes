# Estimated-Taxes
Spreadsheet for keeping track of monthly income in order to pay tax estimates in Georgia, USA.

This is a derived work - based on a spreadsheet published by Mike Sandrik for use with CA and found here:
http://mikesandrik.com/spreadsheets/

He describes most of the spreadsheet in excellent detail on this page:
https://mikesandrik.com/estimated-income-tax-spreadsheet/

I have modified the spreadsheet  and am making it available here, with Mike Sandrick's permission, under the CC0 terms found in the LICENSE.

**NOTE:**  I am not an accountant or CPA.  Just using this to try to make my life easier.

## Summary of changes from the original spreadsheet

1) The tab for CA is removed and replaced with GA - GA starts their taxes from the Fed AGI, so that calculation is a little different from the original.  (GA also has a different deduction structure, and forgives some income in retirement.)  Those fields have been relabeled.   

2) This spreadsheet is updated for 2022 tax tables from the 2021 version I used.   Each year will require updates for these tables and deductions.  GA has changes in 2022, and Internet searches for those changes yield a lot of different results.  I have based the numbers from my best reasoning against the instructions in the tax booklet published for GA for 2022.  Please take care that you feel comfortable with those tables and deductions.

3) New monthly input sections in the Quarterly income tab.  If you edit the names for Jan, that will propagate to the other months.  There's also a YTD summary so you can reconcile against those figures in your statements.

4) I also added a reminder for the Jan est payment that your last years' tax refund can be applied to this year (I do this).  

5) **NOTE:** there is a macro which will recolor the cells in the blocks for Feb-Dec to match Jan.  If you don't like macros, or think it's over the top, or would prefer to highlight different cells for different months, then deleting or disabling the macro has no numeric effects anywhere in the sheet - it's just to color those cells.

6) The formula in cell B20 of the Fed Tax tab  is modified so that lowballing your estimated taxes will not get you in trouble.  If you've made more than you estimated, then it will use that instead of your estimate.  

## How to use this spreadsheet

Yellow highlighted cells are places where you should input your data.  Green highlighted cells are calculated output.  

If you have an estimate on wages or other earned income that you are expecting this year, then enter that in the Federal Income Tax tab at the top left.

As you actually get earned income, you should enter that quarterly, in the Quarterly Income tab.  

If you have various accounts with brokerages, companies, banks or credit unions, then enter the account names in the Quarterly Income tab in the highlighted section under JAN.   The names you enter there are copied to the other months automatically.

For these accounts, you can change the highlighting in the JAN block to show where you expect to see income.   For example, it might make sense to only highlight the Interest cell for Banks and Credit Unions if that is the only sort of income you get from those institutions.   Or alternately, if you are given restricted stock shares or grants, then you might only highlight the Dividends for that account.   If you leave the macro intact, then when you re-color the cells in Jan, the macro will recolor the other months to match.

**Note:**  I'm stll not certain that the macro is worth it.  For example, if your stock pays dividends quarterly, then you might prefer to only highlight the months where you expect to get dividends from that stock.   Also, I will typically NOT open strange spreadsheets with macros enabled.  So, maybe it's better to just set all the highlights manually and remove the macro.  I still haven't decided.  

The Overview tab will tell you if you have paid what you owe.  If not, then you will have to make your estimated payments.  Those are recorded by quarter on the quarterly income tab - and there is a handy cell where you can enter your confirmation numbers there.

If you find this useful and have resonable comments on making it better, pls consider opening an issue.
