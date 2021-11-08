# Election_Analysis

##Project Overview 
Tom, a Colorado Board of Election employee has asked us to work with him to complete an election audit of a recent local congressional election. We need to report: 

1. Toal number of votes cast 
2. Total number of votes for each candidate
3. Percentage of votes for each candidate
4. The winner of the election based on the popular vote
5. The percentage of votes from each county 
6. Which county had the largest turnout

## Resources 
-Data Souce: Election_results.csv 
Software: Python 3.7.6, Visual Studio Code, 1.62.0

## Results
The analysis of the election show that:
-There were 369,711 votes cast in the election.
-The candidates were:
    -Charles Casper Stockham
    -Diana DeGette
    -Raymon Anthony Doane
-The candidate results were:
    -Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
    -Diana DeGette received 73.8% of the vote and 272,892 number of votes.
    -Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
-The winner of the election was:
    -Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.
-The % of votes cast by County were:
    -Jefferson: 10.5% (38,855)
    -Denver: 82.8% (306,055)
    -Arapahoe: 6.7% (24,801)
-The largest Country turnout was Denver with 82.8% 

## Challenge Summary 

Using the tools of Python, Visual Studio Code and the data set, we were able to create a tool which saved a lot of manual counting and can easily be slightly motified to use again for additional elections. We defined our variable, looped through the dataset, checked to see if the vote was for the candidate, and calculated and printed out large totals. 

 By just creating a new text document to save to and by uploading additional csv data results, this scrip can be used again in future elections. If required and the necessary data was collected, it could be motified to count voter turnout by age or by political party. Additional analysis can be collected for the Colorado Board of Elections to study and understand patterns amongst their voters. 
 
 Please disregard my consistant use of the word COUNTRY instead of COUNTY in the code... 
