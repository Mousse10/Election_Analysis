# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election. 

1. Calculate the total number of votes cast. 
2. Get a complete list of candidates who received votes. 
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate won. 
5. Determine the winner of the election based on the popular vote. 

## Resources 
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Summary 
The analysts of the election show that:
- There were 369,711 votes cast in the election. 
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes. 
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes. 
- The winner of the election was: 
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes. 

# Election Audit

## Overview of Election Audit
After providing the above mentioned results, the election commission requested the following additional data to complete the audit:
- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest turnout
This information will enable Seth, Tom and the election commission to have an overview of the results on a county basis. 

## Election-Audit Results
Upon our analysis of the initially provided election data, we found the election outcomes below:
 - A total of 369,711 votes were cast in this congressional election
 - We were able to pull the following breakdown of the number of votes and the percentage of total votes for each county in the precinct: 
 ![](analysis/County%20Breakdown.png)
 - The county with the largest number of vote is Denver. This was calculated using the following script:
![](analysis/Largest%20County%20Script.png)
 - We were able to pull the following breakdown of the number of votes and the percentage of the total votes each candidate received:
![](analysis/Candidate%20Breakdown.PNG)
 - The candidate that won the election is Diana DeGette, she received 73.8% of the vote and 272,892 number of votes. This was calculated using the following script:
![](analysis/Winning%20Candidate%20Script.PNG)
## Election-Audit Summary
In the end, the provided script can be used for research purposes by both the committee and the candidates to figure out where the focus should be in order to run and win elections respectively. This script can be used and modified in a lot of different ways for any election given the data that would be made available. It automates the analysis process and provides a detailed report of the results by going through the entire data set and extracts the important information. These results can be analyzed from different perspectives. The path of the CSV can be modified to analyze a different datasets which include additional criterias. Variables can be modified according to the new dataset data and additional calculations can be made. Changing the printing statements to be relevant and precise to the new election process with additional candidates, counties and results. These are only a few amongs many adjustments that can be made to this script in order for it to be useful in other elections.
