# PyPoll Challenge

## Overview of Election Audit: 
Tom asked that we improve upon the use of Excel to aggregate and certify the election results.  Key metrics include total votes, votes per county, county with largest turnout, candidate summaries including received votes and percentage of total votes, and the overall winner.

## Election-Audit Results:
-How many votes were cast in this congressional election?<br>
![image](https://user-images.githubusercontent.com/100323377/160291969-578fb0aa-5fd4-4473-98f3-48779d85ec8a.png)<br>
-Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.<br>
![image](https://user-images.githubusercontent.com/100323377/160291982-55c6e3a5-2a9c-401a-a641-c7ae72963f96.png)<br>
-Which county had the largest number of votes?<br>
![image](https://user-images.githubusercontent.com/100323377/160291994-3e28bd7b-b80c-41f7-834c-375b25845dc2.png)<br>
-Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.<br>
![image](https://user-images.githubusercontent.com/100323377/160292006-d0f469d5-777b-421c-bc7d-580e6fb8ecdb.png)<br>
-Which candidate won the election, what was their vote count, and what was their percentage of the total votes?<br>
![image](https://user-images.githubusercontent.com/100323377/160292021-e1426147-da6d-4535-a9f2-48d0abc46df1.png)<p/>
## Election-Audit Summary: 
To expand this tool to other elections, the code will nativey pickup incremental counties and can be run for similar races given the same input file, albeit only one race per input sheet.<br>
To expand the usage for this code:<br>
-Include multiple races in this data by importing data set with another column including the race contested, and building incremental loops to solve mutiple races concurrently.<br>
-Run-off functionality can be added to hunt candidates receiving a determined minimum amount of votes to be retained, and eliminating all other candidates. This would be useful in primary elections and other races where a minimum percentage of votes cast are required to meet winning conditions.
