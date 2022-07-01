# Election_Analysis

## Project Overview
A colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who recieved votes.
3. Calculate the total number of votes each candidate recieved.
4. Calcuate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Software: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Summary
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymond Anthony Doane
- The candidate results were:
  - Charles Casper Stockham recieved 23.0% of the vote and 85,213 votes.
  - Diana DeGette recieved 73.8% of the vote and 272,892 votes.
  - Raymon Anthony Doane recieved 3.1% of the vote and 11,606 votes.
- The winner of the election was:
  - Diana DeGette who recieved 73.8% of the vote and 272,892 votes.

## Challenge Overview
Additional coding was required to be able to report on outcomes at the county level.  The following tasks were completed.

1. Get a complete candidate of all counties where votes were cast.
2. Calculate the total number of votes cast in each county.
3. Determinw which county had the largest number of votes.

## Challenge Summary
The analysis showed the following county results.

![County Results](https://user-images.githubusercontent.com/106936638/176801861-1fe38bd8-b9ea-4fad-bd63-ddef1e9ee35a.PNG)

## Election Audit Summary
The script created can be used in future elections because it relies on variables to create custom lists based on the data within the csv files that could be used in the future.  The code could be used for candidate voting in different counties if the files have the same format.  If the files have different column format, the script could be used by modifying the column number when creating the variables.

The script could also be used in other type of voting scenarios.  The code could be updated with different variable names if needed to better match the election being analyzed.  In addition, we could follow the same process to code additional questions or columns that may contain votes on other topics.
