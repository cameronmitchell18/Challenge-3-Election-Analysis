# **Module 3 Challenge - Election Audit** :ballot_box_with_check: :inbox_tray:

## Overview of Election Audit:

Tom and Seth walked us through how we could write a Python script to easily determin the winner of the election from the CSV file we were given. We wanted to know how many voters each county had along with their respected percentages and we wanted to know who the winner of the election was based off how many votes they received and their percentage of the total votes. Determining all of that could have been possible using Excel and working the CSV file but considering the file had 369,711 (not including the header) it would have a been a very laborious and time consuming task. Through a few examples and some practice we were able to write a Python script that did all of the manual work for us. Seth wanted to be able to run the script from his terminal to see the final results, as well as, have it printed out on a txt file for easy distribution. 

## Election-Audit Results:

### Total votes were cast in this congressional election:
 
*   ```
    Election Results
    -------------------------
    Total Votes: 369,711
    -------------------------
    ```

### Number of votes and the percentage of total votes for each county in the precinct:

*   ```
    County Votes:
    Jefferson: 10.5% (38,855)
    Denver: 82.8% (306,055)
    Arapahoe: 6.7% (24,801)
    ```

### County with the largest number of voters: 

*   ```
    Largest County Turnout: Denver
    Winning County in Votes: 306,055
    Winning County in Percentage: 82.8%
    ```

### Number of votes and the percentage of the total votes each candidate received:

*   ```
    Charles Casper Stockham: 23.0% (85,213)
    Diana DeGette: 73.8% (272,892)
    Raymon Anthony Doane: 3.1% (11,606)
    ```

### The winning candidate, their vote count, and the percentage of votes they receieved: 

*   ```
    Winner: Diana DeGette
    Winning Vote Count: 272,892
    Winning Percentage: 73.8%
    ```

## Election-Audit Summary:

I beleive that with a few small changes, this script could work for the Presidential election. You could keep the all of the county information to see which county had the most voters for a given state, along with, which counties voted for which candidate. Also, by creating another Dictionary and List, you could figure out which candidate won each state by interating through the list and adding a vote to for the candidate given from within the state. In theory that would give you the result of who would have won the presidency. The total state count though does not factor in Electoral College votes and so some further scripting would need to be done. If we wanted to just find out though which county voted for who and then which candidate won which state, we could modify the script to do so. 
 


