# Election_Analysis

## Overview
Help Tom and Seth Analyze the election results for the Colorado Board of Elections.

By getting a total vote count of each candidate who received votes.  
Calculating the percentage of each candidate to determine who won the election.

My data resource is the election_results.csv file that I analyzed in Python 3.7 and VS Code 1.65.2 software.

The final analysis of all 3 candidates showed that the winner won with 73.8% of the 369,711 total votes.

## Election Results

```
-------------------------
Total Votes: 369,711
-------------------------

County Votes:
Jefferson: 10.5% (38,855)
Denver: 82.8% (306,055)
Arapahoe: 6.7% (24,801)
-------------------------
Largest County Turnout: Denver
-------------------------
Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)
-------------------------
Winner: Diana DeGette
Winning Vote Count: 272,892
Winning Percentage: 73.8%
-------------------------
```

## Election Audit Summary

- Data files could be provided for the number of registered voters in each county, and the code would be modified by using the number of registered voters as the denominator in the voter turnout calculation %.

- For additional elections, State would be necesasry when evaluating results across states and countries. The files would need a State and Country column, and the code would need to be modified to calculate the county results within each State and Country correctly.

