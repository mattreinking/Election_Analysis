# Election_Analysis

## Project Overview
The Colorado Board of Elections need a list of tasks completed for an election audit on the recent local congressional election.

1. Total number of votes cast
2. A complete list of candidates who received votes
3. Total number of votes each candidate received
4. Percentage of votes each candidate won
5. The winner of the election based on popular vote

## Resources
- Data Source: election_results.csv
- Software: Python 3.10.5, Visual Studio Code 1.69.1

## Election-Audit Results
The analysis of the election show that:

![2022_07_13_17_36_39_election_analysis_Notepad](https://user-images.githubusercontent.com/86776606/178860126-02aafbcb-9d0b-46c3-b4a8-eb53f32cf5f8.png)


- There were 369,711 votes cast in the election

- The counties were: 
  - Jefferson
  - Denver
  - Arapahoe

- The county results were:
  - Jefferson had 10.5% of the total vote at 38,855 number of votes
  - Denver had 82.78% of the total vote at 306,055 number of votes
  - Arapahoe had 6.7% of the total vote at 24,801 number of votes

- The county with the largest number of votes was:
  - Denver with 306,055 number of votes

- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
  
- The candidate results were:
  - Charles Casper Stockham received 23% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.

- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

## Election-Audit Summary
The script used for this election involved only 3 counties in the state of Colorado. It can be easily utilized to track counts for all counties of Colorado. The code is highly efficient using a csv file which is a file of the data arranged into a simple and malleable format. Keeping the data flexible allows for great potential to expand structure with ease. With how fundamental the data stays this script could expand to tracking counts for all cities and even as far as tracking for all states in the country.

![image](https://user-images.githubusercontent.com/86776606/178872425-9814fe4d-7dd0-4507-aea9-bb34b6d87c5c.png)

The code displayed shows how easy it can be to re-arrange and substitute the data variables to match the scaling of the project. The naming conventions used for creating the list and dictionary and voter turnout can also represent cities and states if the intent is to capture results for larger/multiple election boards.
