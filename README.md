# election-analysis
---
# Analysis of Election Results
## Overview of Election Audit
The purpose of this election audit was to create code using Python in order to analyze the results of an election and to output the candidates, the number of votes they received, and the percentage of the total votes they received.  Additionally, the it will ouput the percentage of the total votes which came from each county and which county had the highest voter turnout.  Finally, the code is written in a way so that it could be used to analyze any election results which are stored in a .csv file of the same format.  This way the code can be reused by the client for future election analyses.

## Election Audit Result
- Total Vote Count:
    - 369,711
- Votes by County:
    - Jefferson: 10.5% (38,855)
    - Denver: 82.8% (306,055)
    - Arapahoe: 6.7% (24,801)
- Largest County Turnout:
    - Denver
- Votes by Candidate:
    - Charles Casper Stockham: 23.0% (85,213)
    - Diana DeGette: 73.8% (272,892)
    - Raymon Anthony Doane: 3.1% (11,606)
- Election Result
    - Winner: Diana DeGette
    - Winning Vote Count: 272,892
    - Winning Percentage: 73.8%  
## Election Audit Summary
The code used in order to perform this analysis can be quite easily repurposed in order to be used for any election, given some very minor modifications.  One way this script can be modified is that the file paths for both the .csv file to be read and the .txt file to write the ouputs, can be easily changed to any path by altering the value of the 'file_to_load' and 'file_to_save' variables respectively.  Also, if the columns happen to be in a different order, the indexes used to call up 'candidate_name' and 'county_name' can be changed to represent the correct columns.  Since the lists and dictionaries used in this code are declared as open, the code should be able to accomodate any number of candidates and counties.
