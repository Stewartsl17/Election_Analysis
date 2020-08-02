# Election_Analysis

## Project Overview 
Tom, a Colorado Board of Elections employee, has tasked us with completing the election audit of a recent local congressional election. In order to replicate this process for future elections, our client wanted us to write script in Python. The steps of the script are as follows: 

1. Open the data file.
2. Write down the names of all the candidates.
3. Add a vote count for each candidate.
3. Get the total votes for each candidate.
4. Get the total votes cast for the election.

After finalizing that task for Tom, he then wanted us to add the additional county-level data points to our audit:

1. The voter turnout for each county
2. The percentage of votes from each country out of the total count 
3. The country with the highest turnout

## Resources 
* Data Sources: [Election_results.csv](https://github.com/Stewartsl17/Election_Analysis/blob/master/Resources/election_results.csv)
* Software: Python 3.8.5, Visual Studio Code, 1.47.3

## Election - Audit Results 

### Candidate Summary 
The [analysis](https://github.com/Stewartsl17/Election_Analysis/blob/master/Analysis/election_results.txt) of the elections shows that: 
* There were 369,711 votes cast in the election. 
* The candidates were: 
  * Charles Casper Stockam
  * Diana DeGette
  * Raymond Anthony Doane
* The candidates results were: 
  * Charles Casper Stockam recieved 23% of the vote and 85,213 votes 
  * Diana DeGette recieved 73.8% of the vote and 272,892 votes 
  * Raymond Anthony Doane recieved 3.1% of the vote and 11,606 votes 
* The winner of the election was: <br>
   * __Diana DeGette, who recieved 73.8% of the vote and 272,892 votes__
 
### County Summary 
* The counties for this election were:
  * Jefferson County
  * Denver County
  * Arapahoe County
* The county results were: 
  * Jefferson County accounted for 10.5% of the the total vote with 38,855 votes
  * Denver County accounted for 82.8% of the the total vote with 306,055 votes
  * Arapahoe County accounted for 6.7% of the the total vote with 24,801 votes
* The county with the highest turnout was:
  * __Denver County, which accounted for 82.8% of the the total vote with 306,055 votes__

## Election - Audit Summary 

We could also modify this script for additional analyses that the Board of Elections might need. If we added more variables to the data file, we could look into key demographic metrics such as race, gender, age, household income, education, and employment. These metrics are crucial in elections as politicians need to understand all aspects of their voter base in order to create the right platform for elections. The script could also be adjusted to target state level elections instead of congressional districts. One other way that this script could be modified is looking into voter turnout in urban vs. suburban vs. rural areas and see if there are ways in which they can tap into voter bases that aren't as strongly represented. 
 
 
 
  
