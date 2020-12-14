# Election_Analysis

## Overview of Election Audit 
Seth and Tom requested assistance in submitting the election audit results to the election committe. After the election results were submitted, the election committe requested
additional data to complete the audit. Working with the module's election results file, we were to use for loops and conditional statements with logical operators to figure out 
the voter turnout for each county, the percentage of votes from each of the county, and the county with the highest turnout. The two softwares that we used to complete the tasks
were Python 3.7.6 and Visual Studio Code.   
## Election Audit Results
1. How many votes were cast in this congressional election?<br/>
In this congressional election, there was a total of 369,711 votes casted.<br/><br/>
2. Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
The counties in the precinct were:
- Arapahoe<br/>
- Denver<br/>
- Jefferson<br/><br/>
The county results were:
- Arapahoe had 24,801 votes and a percentage of 6.7% of the total votes.</br>
- Denver had 306,055 votes and a percentage of 82.8% of the total votes.</br>
- Jefferson had 38,855 votes and a percentage of 10.5% of the total votes.</br></br>
Below is the code to retrieve the county results. 
![countyvotes](https://github.com/echuung94/Election_Analysis/blob/main/Resources/countyvotes.png)
3. Which county had the largest number of votes?<br/>
Denver had the largest number in the county, with 306,055 votes.<br/><br/>
4. Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
The candidates in the election were: 
- Charles Casper Stockham<br/>
- Diana DeGette<br/>
- Raymon Anthony Doane<br/><br/>
The candidate results were:
- Charles Casper Stockham received 23.0% of the votes and 82,312 number of votes.<br/>
- Diana DeGette received 73.8% of the votes and 272,892 number of votes.</br>
- Raymon Anthony Doane received 3.1% of the votes and 11,606 number of votes.<br/><br/>
5. Which candidate won the election, what was their vote count, and what was their percentage of the total votes?<br/>
Diana DeGette won the election with 272,892 number of votes and a percentage of 73.8% of the total vote.<br/><br/>
Below is an overview of the entire election results.<br/>
![electionresults](https://github.com/echuung94/Election_Analysis/blob/main/Resources/electionresults.png)

## Election Audit Summary
This script can be used to retrieve information needed for the names of the candidates that are running for an election along with the counties that they are
running in. With the for loops and if functions, we are able to retrieve information which includes: the total number of votes in the election, the number of votes in 
a specific county and the percentages of the total votes. One example the script could be modified would be to rewrite the script altering the script within the for loop
to find the candidate with the largest or smallest amount of votes in a particular county. Another example would be to add the previous years election results in the csv 
file and use the data to compare the votes within the three counties in two different years. 
