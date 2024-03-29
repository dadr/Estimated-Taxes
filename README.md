# Estimated-Taxes
Spreadsheet for keeping track of monthly income in order to pay tax estimates in Georgia, USA.

This is a derived work - based on a spreadsheet published by Mike Sandrik for use with CA and found here:
http://mikesandrik.com/spreadsheets/

He describes most of the spreadsheet in excellent detail on this page:
https://mikesandrik.com/estimated-income-tax-spreadsheet/

I have modified the spreadsheet  and am making it available here, with Mike Sandrick's permission, under the CC0 terms found in the LICENSE.

**NOTE:**  I am not an accountant or CPA.  Just using this to try to make my life easier.

## Summary of changes from the original spreadsheet(s)

1) The tab for CA is removed and replaced with GA - GA starts their taxes from the Fed AGI, so that calculation is a little different from the original.  (GA also has a different deduction structure, and forgives some income in retirement.)  Those fields have been relabeled.   ALSO note that GA does not tax Social Security, but this version of the spreadsheet has not been modified to take that into account.  I suppose I'll make those changes when I start getting a SS payment.

2) This spreadsheet is updated for 2024 tax tables from the previous versions.   Each year will require updates for these tables and deductions.  GA has major changes in 2024, and Internet searches for those changes yield a lot of different results.  I have based the numbers from GA sources, or if not available, then the most conservative online source. There is not yet a tax booklet published for GA for 2024.  Please take care that you feel comfortable with those tables and deductions.

3) New monthly input sections in the Quarterly income tab.  If you edit the names for the rows in Jan, that will propagate to the other months.  Also, once you enter a value in January, there is conditional formatting to highlight that cell in subsequent months.  This replaces the macro that did a similar thing in previous spreadsheets. There's also a YTD summary so you can reconcile against those figures in your statements.

4) I also added a reminder for the Jan est payment that your last years' tax refund can be applied to this year (I do this).  

5) **NOTE:** There is no more macro.  It's deleted and was a major hassle.  See #3 above.

6) The formula in cell B21 of the Fed Tax tab  is modified so that lowballing your estimated taxes will not get you in trouble.  If you've made more than you estimated, then it will use that instead of your estimate.  

7) New for 2023 - The federal estimation tab adds a self-employment estimation, and treats Business and Other income from the quarterly tab as self-employment income.  It will calculate  the SE Tax owed to the Fed, and will show higher effective tax rates from this.  The payments include the SE Tax owed.   The Quarterly Income Tab adds monthly boxes to input wages, taxes withheld, and Other Business Income.  These are now calculated boxes for each quarter.  The 2024 spreadsheet also calculates that you will deduct 50% of your Self Employment tax from your regular income tax.  I'm still trying to figure out whether there is a common 20% business income deduction that should become part of the spreadsheet.

8) New for 2024 - The file format for the spreadsheet is now .ods - as I'm using LibreOffice Calc as my main spreadsheet.  Excel users should still be able to make use of this file format.

## How to use this spreadsheet

Yellow highlighted cells are places where you should input your data.  Green highlighted cells are calculated output.  

If you have an estimate on wages or other earned income that you are expecting this year, then enter that in the Federal Income Tax tab at the top left.

As you get income, you should enter that monthly, in the Quarterly Income tab.  

If you have various accounts with brokerages, companies, banks or credit unions, then enter the account names in the Quarterly Income tab in the highlighted section under JAN.   The names you enter there are copied to the other months automatically.

For these accounts, once you enter an amount in the JAN block (even $0) the sheet will highlight that block and all the same blocks in other months to show where you expect to see income.   For example, you enter interest for a bank in January, and the sheet will highlight the interest cell for that bank for the rest of the year.

The Overview tab will tell you if you have paid what you owe.  If not, then you will have to make your estimated payments.  Those are recorded by quarter on the quarterly income tab - and there is a handy cell where you can enter your confirmation numbers there.

If you find this useful and have resonable comments on making it better, pls consider opening an issue.
