# Election Results Analysis

## Overview of Election Audit:
- **Purpose**
<br>In this project, we are using Python to work through all the vote data from an election, aiming to summarize the vote count, vote percentage by each county, as well as each candidate accordingly, so that we can provide a clear overview of the elecion results, including winning candidate and largest vote county.

## Election-Audit Results
Please refer to [election_results](https://github.com/Ilylsh/Election_Analysis/blob/4af7ccf1cfef5e0f4aa970947f5506df2d547609/analysis/election_results.txt) for the breakdown details.
- **How many votes were cast in this congressional election?**
<br> Total 369,711 votes were cast in the election

- **Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.**
<br> Please see the breakdown of the number of votes and the percentage of total votes by county:
<br> County Votes: 
<br> Jefferson: 10.5%,(38,855)
<br> Denver: 82.8%,(306,055)
<br> Arapahoe: 6.7%,(24,801)

- **Which county had the largest number of votes?**
<br> Based on the analysis, Denver had the largest number of votes.

- **Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.**
<br> Please see the breakdown of the number of votes and the percentage of total votes by candidate:
<br> Charles Casper Stockham: 23.0% (85,213)
<br> Diana DeGette: 73.8% (272,892)
<br> Raymon Anthony Doane: 3.1% (11,606)

- **Which candidate won the election, what was their vote count, and what was their percentage of the total votes?**
<br> Among 3 candidates, Diana won the most votes, with total votes of 272,892 and 73.8% of the total votes.

## Election-Audit Summary
In conclusion, this script is versatile and powerful to help demonstrate a clear overview of the election results in an efficient manner. Currently we can easily get a breakdown of the votes by candidate and county. Even if we add more data into the dataset, we can simply modify the script to meet the analysis needs. 
<br>**For Example:**
- *Anlaysis of voting method: by mail or by voting machine*
<br> Create a voting method list and voting method dictionary, use for loop with membership and logical operators to find the count of each voting method.
- *Analysis of votes by state:*
<br> Create a state list and state votes dictionary, use for loop and conditional statement with membership and logical operators to provide the same granular analysis of the election results. Such as total votes, vote percentage by each state, the state with the most votes.  

