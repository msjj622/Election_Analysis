#  Analysis of the Election Audit
## Overview of Election Audit: (Explain the purpose of this election audit analysis.)
The purpose of this election analysis is to gather additional data from original election audit result. The election commission has requested more data about the voter turnout for each county, the percentage of votes from each county out of the total count, The county with the highest turnout as wwell as winner candidate with count of winning vote and percentage of the winning votes.


## Election-Audit Results: (Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.) 
(There is a bulleted list where each election outcome is addressed)

- How many votes were cast in this congressional election? 
369,711 votes. I added to the total vote count (initial value) with this code.
![total_votes_code] (link)

Once you put this code, you will see this print text as image below.


- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  - Jefferson: 38,855 votes and 10.5%
  - Denver: 306,055 votes and 82.8%
  - Arapahoe: 24,801 votes and 6.7%

I created f-string and dictionary first and used 'for' loops and conditional statements to print the requested results. I printed county name to print each row and wrote an 'if' statement that checks that the county does not match any existing county in the county list then add the existing county to the list of counties by using 'append' and tracked the each county's vote count with using strings and dictionary I created at the first step and put '0' values. lastly, add a vote to that county's vote count with same as strings and dictionary with a value of '+= 1'.
![county_list_votes_code] (link)
![county_votes_percentage_code] (link)

Once you put this code, you will see this print text as image below.


- Which county had the largest number of votes?
Denver

I wrote a decision statement with a logical operator to get which county got the most votes.
![largest_county_votes_code] (link)


- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  - Charles Casper Stockham: 85,213 votes and 23.0%
  - Diana DeGette: 272,892 votes and 73.8%
  - Raymon ANthony Doane: 11,606 votes and 3.1%

I created f-string and dictionary first and used 'for' loops and conditional statements to print the requested results. I printed candidate name to print each row and wrote an 'if' statement that checks that the candidate name does not match candidate options then add candidate option to the list of candidate names by using 'append' and tracked the each candidate's vote count with using strings and dictionary I created at the first step and put '0' values. lastly, add a vote to that candidate's vote count with same as strings and dictionary with a value of '+= 1'.
![Candidate_name_list_votes_code] (link)
![candidate_votes_percentage_code] (link)


- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
Diana DeGette: 272,892 votes and 73.8%

I wrote a decision statement with a logical operator to get who got the most votes among the candidates.
![winning_candidate_votes_code] (link)


##Election-Audit Summary: 
(In a summary statement, provide a business proposal to the election commission on how this script can 
be used—with some modifications—for any election. Give at least two examples of how this script can 
be modified to be used for other elections.) 
(There is a statement to the election commission that explores 
how this script can be used for any election, with two examples for modifying the script.) 

The first example I could use with this script to show the result of election for a president or minister of one of countries and show the winning story of which states and regions got the most votes out of total votes. It could also give some ideas to people which states apt to have what political aspects.

Another example I could use is to show a story of winning senator. senator is also elected by votes. now it could be narrow the regions. but thie result could give some ideas of which areas in town are positively willing to participate voting for a senator.