# Election Analysis

## Overview of Election Audit
The purpose of this project is to audit the results of an election to confirm the winner and provide additional details about the election. The data for the audit and analysis comes from a CSV file. Each row of the CSV file represents one ballot or vote containing three pieces of information per row (Ballot ID, County, & Selected Candidate). The ballots will be counted to report on the number of votes each candidate received and confirm the winner. Additional information will also be provided such as county voting statistics from the election.

## Election Audit Results

### Audit Results

* Total Votes Cast: 369,711

* The congressional district for this election includes the three counties shown below with their turnout statistics. 
  * By a large margin, Denver County had the largest share of votes case with 306,055.

	| County    | Ballots Cast | Percent of Total |
	| --------- | ------------ | ---------------- |
	| Jefferson | 38,855       | 10.5%            |
	| Denver    | 306,055      | 82.8%            |
	| Arapahoe  | 24,801       | 6.7%             |

* Three candidates received votes in the election.
  * Diana DeGette won the election in somewhat of a landslide winning 73.8% of votes cast or 272,892 votes.

	| Candidate               | Votes        | Percent of Total |
	| ----------------------- | ------------ | ---------------- |
	| Charles Casper Stockham | 85,213       | 23.0%            |
	| Diana DeGette           | 272,892      | 73.8%            |
	| Raymon Anthony Doane    | 11,606       | 3.1%             |

* Provided below is a copy of the analysis provided to the election commission.
  * ![Election Audit Results](/Resources/Election_Analysis.png)


## Election Audit Summary

In summary, the method used to perform the audit and provide the analysis above can be used for any election. Assuming the input data is in the same format provided for this analysis. Provided below is a list of a few modifications that would help support this effort.

### Suggested modifications:
1. Currently the python script requires each analysis to use the same file name for every election. To be used on any election, the script should be modified to ask the user for the filename and the path to the file.
2. The output of the script should be changed to print a name and date identifying the election along with the filename being audited. This would prevent confusion regarding which election for which the audit was completed.
3. With a couple of additional pieces of information additional insights could also be provided during the analysis. For example, if the number of registerd voters was provided for each county, the turnout of registered voters could be calculated.
