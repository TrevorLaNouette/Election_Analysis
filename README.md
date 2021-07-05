# *Election_Analysis*

## Election Audit Overview

In this project I  was tasked with creating a python code that analizes the data of an election Colorado to assist in an audit. Members of the Colorado board of electons asked me to:

* Calculate the total number of votes cast.
* Get a complete list of candidates who recieve votes.
* Calculate the total number of votes each candidate recieved.
* calculate the percentage of botes each candidate won.
* determine the winner of the election based on popular vote.

- After creating this code, I was asked to expand upon the election analysis by adding the voter turn out for each county, the percentage of votes from each county out of the total count, and the county with the highest turn out.


# Resources 
-Data source: election_results.csb 
-Software: Python 3.7.6, Visual Studio Code , 1.57.1, Git Bash (to upload)


## Election-Audit Results: Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.


* There were 369,711 votes in this congressional election
* The percentage of votes and number of votes in each county are shown below

![County Votes](https://user-images.githubusercontent.com/82718969/124504337-e14cd180-dd8c-11eb-8317-0e5e36592a68.png)


The county with the largest voter turnout with 306,005 votes was:

![Largest County Turnout](https://user-images.githubusercontent.com/82718969/124504374-f6296500-dd8c-11eb-9ac9-0c332d8bf128.png)


The breakdown of the number of votes and percentage of votes are shown below with vote percentage and votes received:

![Candidate Vote Breakdown](https://user-images.githubusercontent.com/82718969/124504401-03deea80-dd8d-11eb-9098-793e16154845.png)

The winner of the election was:

![Candidate Winner](https://user-images.githubusercontent.com/82718969/124504426-0fcaac80-dd8d-11eb-9ab0-a282e1c95191.png)


- Election-Audit Summary: 

A great thing about the use of this code is that it can be used to for any election as long as the data can be input with the same categories of the CSV files. If data is given in the same categorys presented then the code will be able to analize the vote of any election with different candidates names and counties than the ones presented in this election.

To make this code evenmore versatile, small adjustments can be made to the verbage of the code to analize results of other mediums. This would make it effective in analizing questionairs or surveys by changing the outputing messages in the txt files to line up with the desired results. So if you were looking at favorite flavor ice cream by city you would need to change the print messages from (Election results to Favorite flavor results, county votes to city votes, etc... 
As long as the names of the different categories are switched in the print and write messages to the txt files and messages and the CSV data names are included the code will analize the data properly. For exaple, the categories of the cadidates names and or county names simply need to be replaced by the categories being analized in the the new medium. The versatility of this code allows it to be used in pratically any field.

