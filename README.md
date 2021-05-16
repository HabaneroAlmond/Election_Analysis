# Election Audit Analysis

# Overview of Election Audit: Explain the purpose of this election audit analysis.
The purpose of this election audit was to give the election commission more information about how the county turnout and how they were voting. This is important information, not just as it relates to elections. Knowing the voter turnout and the way a county voter base behaves has far reaching financial, and social applications.

# Election-Audit Results:
 - There were 369,711 total votes cast in this election. We were able to calculate this by first initializing a variable that we called 'total_votes' which we gave a value of zero. This variable is called an accumulator and we give it a value of zero to start because we want the variable to iterate through the rows of data and add 1 every time it goes through a row or 'vote'. We get our variable to iterate through the rows by first reading the headers, and then iterating through the rows by adding a value of 1 each time it passes a row. ![total_votes_code](https://user-images.githubusercontent.com/82848585/118405810-7d891080-b647-11eb-9c11-26538c9d50fa.png)
- The majority of the votes cast in this election came from Denver county, nearly 83%! Jefferson and Arapahoe county only accounted for about 11% and 7% respectively.
Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
- This election was a bit of a landslide, with Diana DeGette coming in with 73% of the total votes received. DeGette's vote count was 272'892.
# Election-Audit Summary: 
This script can be easily tweaked to tally votes and provide county voter data in other elections. One way would be to simply change the csv file being retrieved from the os.path. as long as the file is organized with the information in the same columns and rows the script will give us the same information for a different election. If you wanted to use this script to tally a different type of election, presidential for example, you could rename all of the 'county' variables to 'state' or if the vote was not for candidates but for a new law you could change the 'candidate' values to whatever you wanted to abbreviate the new amendment option with.
