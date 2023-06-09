# Election Analysis - Module 3 Challenge
<sub>Chapel Hill - Data Science Bootcamp</sub>

## Overview of Project
For Module 3, Python was used to calculate and display the results of a small-scale election in Colorado spanning the counties of Jefferson, Denver, and Arapahoe. The election data was given in a .csv file containing voter IDs (acting as primary keys to identify each vote as a single person), the county in which the vote was cast, and the candidate that received the vote. Using this information, the python script computed the total number of votes, the number and percentage of votes from each county, and the number and percentage of votes each candidate received. From these numbers, the county with the largest turnout and the winning candidate were also calculated.

## Results
- Total Votes: 369,711
- County Breakdown:
	- Jefferson: 38,855 votes (10.5% of total)
	- Denver: 306,055 votes (82.8% of total)
	- Arapahoe: 24,801 votes (6.7% of total)
		- Largest County Turnout: Denver

![County Breakdown](/images/County_Breakdown.png)
- Candidate Breakdown:
	- Charles Casper Stockham: 85,213 votes (23.0% of total)
	- Diana DeGette: 272,892 votes (73.8% of total)
	- Raymon Anthony Doane: 11,606 votes (3.1% of total)
		- Candidate Winner: Diana DeGette with 272,892 votes (73.8% of total votes)

![Candidate Breakdown](/images/Candidate_Breakdown.png)

## Summary
The current code works well for small-scale county-level elections, but could be reworked to efficiently calculate and analyze different types of elections. Once the script is initiated, it could ask the user which type of election is being analyzed and where the file with voter data is located for ease of use. Depending on the election type, the python file could also call on different functions to calculate the winner rather than having a singular function spanning the entirety of the file. One function could be for county-level elections, where the victor is decided by the total number of votes. Another fuction could be created for state-level elections, where each district's result then determines the winner. A third function could be used for country-level elections, where state-level results are used to calculate each state's electoral votes, which can then be used to conclude the overall victor.
