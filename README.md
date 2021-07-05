# *Election_Analysis*

## Election Audit Overview

In this project I  was tasked with creating a python code that analizes the data of an election Colorado to assist in an audit. Members of the Colorado board of electons asked me to:

* Calculate the total number of votes cast.
* Get a complete list of candidates who recieve votes.
* Calculate the total number of votes each candidate recieved.
* calculate the percentage of botes each candidate won.
* determine the winner of the election based on popular vote.

After creating this code, I was asked to expand upon the election analysis by adding the voter turn out for each county, the percentage of votes from each county out of the total count, and determine the county with the highest vote turnout.


# Resources 
Data source: election_results.csv 

Software: Python 3.7.6, Visual Studio Code , 1.57.1, Git Bash (to upload)


## Election-Audit Results:


* There were 369,711 votes in this congressional election
* The percentage of votes and number of votes in each county are shown below

![County Votes](https://user-images.githubusercontent.com/82718969/124504337-e14cd180-dd8c-11eb-8317-0e5e36592a68.png)


* The county with the largest voter turnout with 306,005 votes was:

![Largest County Turnout](https://user-images.githubusercontent.com/82718969/124504374-f6296500-dd8c-11eb-9ac9-0c332d8bf128.png)


* The breakdown of the number of votes and percentage of votes are shown below:

![Candidate Vote Breakdown](https://user-images.githubusercontent.com/82718969/124504401-03deea80-dd8d-11eb-9098-793e16154845.png)

* The winner of the election was:

![Candidate Winner](https://user-images.githubusercontent.com/82718969/124504426-0fcaac80-dd8d-11eb-9ab0-a282e1c95191.png)


- Election-Audit Summary: 

A great thing about the use of this code is that it can be used for any election. The data file can be input with different county and candidate names and the code will adapt the new information. This is because the code will create a new candidate name or county name if it does not currently exsist in the list. This key feature allows the code to be adaptable to new data.

To make this code evenmore versatile, small adjustments can be made to the verbage of the code to analize results of other mediums. This would make it effective in analizing questionairs or surveys by changing the outputing print messages and txt files to line up with the desired results of the new data. For example, if you were looking analizing data of favorite flavor ice cream by city you would need to change the print and write messages from (Election Results to Favorite Flavor Results, County Votes to City Votes, etc... 

Updating these print and write to match the new data will allow the code to output the results properly. The versatility of this code allows it to be used in pratically any field.

