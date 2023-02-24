Overview of Election Audit: Explain the purpose of this election audit analysis.
The purpose of this election audit analysis is to see the turnout for each county,votes, and the total percentage for each county. This will allow you to see the highest total count before submiting the results.

Election-Audit Results: Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.

How many votes were cast in this congressional election?
For this election there were 369,711 votes cast. 
Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

Which county had the largest number of votes?
Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
County Votes:Jefferson: 10.5% (38,855),Denver: 82.8% (306,055),Arapahoe: 6.7% (24,801)
# 6a: Write a for loop to get the county from the county dictionary.
    for county in county_votes:
        # 6b: Retrieve the county vote count.
        county_vote=county_votes[county]
        # 6c: Calculate the percentage of votes for the county.
        county_percentage=float(county_vote)/float(total_votes)*100

         # 6d: Print the county results to the terminal.
        county_results = (
        f"\nCountyResults\n"
        f"-------------------------\n"
        f"{county} {county_percentage} {county_vote}\n"
        f"-------------------------\n\n"
        f"County Votes:\n")
        print(county_results, end="")

Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
Diana DeGette won the election. Her vote count was 272,892, with a percentage of 73.8%.
Election-Audit Summary: In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.
This script can be used for any elections with small modifications and I can give you two examples of how you can apply this script. Example one, lets say you're in a mega church and you have three pastors who are inquring about being the pastor at this church. instead of using county names, you will change it to pastoral names. Second example would be class president at a high school. Instead of using county names, you would use student names. 

