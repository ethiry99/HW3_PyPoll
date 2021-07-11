# Module 3 | Assignment - PyPoll

## Overview of Election Audit

### The purpose of the election audit analysis is to:

    * Count the number of votes cast.
    * Provide breakdown of votes and percentage of votes for each county in the precinct.
    * Determine which county had the largest number of votes.
    * Provide a breakdown of the number of votes and percentage of the total by candidate.
    * Determine the winning candidate, their vote count, and percentage of the total vote.

These results will be displayed on the screen and to a text file (election_analysis.txt).

## Election-Audit Results

### Total Number of Votes

The total number of votes was 369,711. It was calculated using the follow code:

![](https://github.com/ethiry99/HW3_PyPoll/blob/main/Resources/Total_Vote_Code.png)

### Breakdown of Votes and % of Total Votes by County in the Precinct

The breakdown of votes and percent of the total by county came out like:

![](https://github.com/ethiry99/HW3_PyPoll/blob/main/Resources/Outcome_by_County_output.png)

The code to count the votes by county was written like this:

[Code to calculate and display county results.](https://github.com/ethiry99/HW3_PyPoll/blob/main/Resources/Outcome_by_county_code.png)

### Determine the County with the Largest Number of Votes

The county with the largest number of votes was Denver. The code to determine the largest turn out looked like:

![](https://github.com/ethiry99/HW3_PyPoll/blob/main/Resources/Largest_County_turnout_code.png)

### Breakdown the Number of Votes and the Percentage of Total Votes by Candidate

The number of votes and percentage by candidate results looked like this:

![](https://github.com/ethiry99/HW3_PyPoll/blob/main/Resources/Vote_by_Candidate_output.png)

The coding for this results was completed as such:

[Code to display the results by candidate](https://github.com/ethiry99/HW3_PyPoll/blob/main/Resources/Vote_by_Candidate_display_code.png)

### Determine the Winning Candidate and Display Name, Vote Count, and % of Total Vote

The winning candidate information was determined to be:

![](https://github.com/ethiry99/HW3_PyPoll/blob/main/Resources/winner_output.png)

These results and display were created by the code as shown below:

# Insert winning cadidate code

## Election-Audit Summary

Now that this election audit summary has been completed, it may be time to review other ways that it can used to assist in auditing election results.

### Expand to Other Precints

This algorithm could be used for any precinct or multiple precincts at the same time.  In order to process multiple precincts the label of which precinct is being counted would need to be included in the data file.  Some additinal coding would also be required to track results by precinct instead of just a single precinct in the audit that was completed here.

### Track Multiple Races Within a Precinct 
In the program created for this request only a single race was tracked.  It could be expanded to handle multiple races within a precinct.  A mayoral race, at large city council, city attorney, planning department of even for a ballot inititive could all be tracked in a single analysis.  By adding a column to the source data for "electoral_race_name", each precinct could have multiple races tracked.  This would also require some additional coding but the bulk of the program as already been written during this analysis. 




   
   
    



