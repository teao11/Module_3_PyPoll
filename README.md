# Module_3_PyPoll

<h3>Overview of Election Audit</h3>
The purpose of the election analysis was to put in to practice what we had learnt throughout the third module. We leveraged our knowledge of Python variables, objects, methods, data structures to read from a CSV of election results, analyze and display who won before writing to an output txt file.

<h3>Election-Audit Results</h3>
After running the analysis, I output the following results to the terminal / wrote to the txt file:

<img width="563" alt="Screen Shot 2021-05-22 at 10 49 24 AM" src="https://user-images.githubusercontent.com/46773181/119236281-6173ec00-baeb-11eb-9d60-a1f3553d4190.png">

In total, there were 369,111 votes cast in this congressional election. These votes were from 3 different counties and for 3 different candidates.

<img width="181" alt="Screen Shot 2021-05-22 at 10 58 32 AM" src="https://user-images.githubusercontent.com/46773181/119236511-a6e4e900-baec-11eb-9740-5b280476b7cb.png">

As you can see in the screenshot above, the largest county (in terms of vote volume) was Denver with 82.8% (306,055) of the votes. The second was Jefferson with 10.5% (38,855) followed by Arapahoe with 6.7% (24,801) votes.

Denver had the greatest number of votes with 82.8% (306,055).

<img width="288" alt="Screen Shot 2021-05-22 at 10 58 08 AM" src="https://user-images.githubusercontent.com/46773181/119236496-99c7fa00-baec-11eb-8927-c38ec974502c.png">

As you can see in the output above, Charles Casper Stockham received 23.0% (85,213) of the votes, Diana DeGette received 73.8% (272,892) of the vote, and Raymon Anthony Doane received 3.1% (11,606) of the votes.

<img width="199" alt="Screen Shot 2021-05-22 at 10 57 50 AM" src="https://user-images.githubusercontent.com/46773181/119236485-8f0d6500-baec-11eb-9af8-048ebd9297ac.png">

Diania DeGette won the election by a massive margin, with 73.8% (272,892) of the votes.

<h3>Election-Audit Summary</h3>

Dear Election Committee,

This script we have created here is flexible and can be used to analyze the election results of any election where the votes are being aggregated by counties. If there are more than 3 candidates, it will detect that and aggregate the votes accordingly for the analysis. It will also do the same thing for the number of counties

If I were to suggest a couple areas for modification, the first would be altering the script to analyze by a different geographic area (Cities / towns, zipcodes) in order to get a more granular look at where the votes are coming from and who they are for.

In it's current state, this script only analyzes results from candidates running against each other. Perhaps it could be augmented to analyze multiple different elections at once, so that you do not have to run multiple jobs here.
