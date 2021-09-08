# Election_Analysis
## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complee the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of hte election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7, Visual Studio Code, 16.11.2

## Summary
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
  - Candidate Diana DeGette, who received 73.8% of he vote and 272,892 number of votes.


## Challenge Overview
The election comission has requested additional data to complete the audit, including:

1. The voter turnout for each county
2. The percentage of votes fro meach county out of the total count
3. The county with the highest turnout

## Challenge Summary
- There were 369,711 votes cast in the election
- The counties included in the precint include:
  - Jefferson
  - Denver
  - Arapahoe
- The county results were:
   - Jefferson: 38,855 votes cast (10.5%)
   - Denver: 306,055 votes cast (82.8%)
   - Arapahoe: 24,801 votes cast (6.7%)
- The county with the largest vote total was Denver, with 306,055 votes (82.8%)

## Election Audit Summary
The code written for this analysis can be reused or modified for future election audits.  If the election data is provided in a similar structure, the csv reference could easily be changed to reference a new file.  Otherwise, index references could be easily changed, or even excluded, if data isn't provided in the same order, or if county detail isn't provided.  The code could even be adopted for a national election audit, with State vote detail, rather than counties.

## Terminal and .TXT Outputs
![txtfile](https://user-images.githubusercontent.com/88443672/132582338-9a0e79c6-8a59-4eb9-aa29-cc26f0f7a1d1.png)
![terminaloutput](https://user-images.githubusercontent.com/88443672/132582325-c0db3d9f-ce84-4bba-93f1-5b69d497050e.png)

