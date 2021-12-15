![Vote pic](https://user-images.githubusercontent.com/93869894/144725943-a3cc5e49-477a-4422-b82d-0e1f283cc9d2.png)

## Election_Analysis

## Project Overview
A local congressional election was held in Colorado and a memeber of the BOard of Elections assigned the task of auditing the election results to me.  The following is the process I took to complete the audit:
  1. Calculate the total number of votes cast.
  ![Calculate votes cast](https://user-images.githubusercontent.com/93869894/144725923-074a1fd4-5f9a-46a6-b0bd-bec416926c56.png)
  2. Obtain a complete list of candidates running in the election who reveived votes.
  ![Who received votes](https://user-images.githubusercontent.com/93869894/144725891-91b5581e-59bc-4900-ae64-cab589dbcd01.png)
  3. Calculate the number of votes each cansdidate received.
  ![Calculate votes cast](https://user-images.githubusercontent.com/93869894/144725900-f9ff8c25-45e4-4e1b-86cf-c5f57aafa48f.png)
  4. Calculate the percentage of votes case for each candidate.
  ![Percentage of vote received](https://user-images.githubusercontent.com/93869894/144725905-6c51f6ef-23f8-4965-803d-968b21d5e871.png)
  5. Determine wht winner of the election based on popular vote.
  ![Winner of election](https://user-images.githubusercontent.com/93869894/144725915-cbf60370-042f-4be5-80d3-be80b36bc63b.png)

## Resources

  Data Source: election_results.csv
  software: Python 3.7.6, Visual Studio COde, 1.62.3
  
## Summary
  The analysis of the election show that:
  
    There were 369,711 votes cast in the election.
    Breakdown by county:
      Jefferson: 38,855 votes (10.5% of the total votes)
      Denver: 306,055 votes (82.8% of the total votes)
      Araphone: 24,801 votes (6.7% of the total votes)
    The candadates were:
        Charles Casper Stockham
        Diana DeGette
        Raymon Anthony Doane
    The candidate results were:
        Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes
        Diana DeGette received 73.8% of the vote and 272,892 number of votes
        raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes
        
    The winner of the election was:
        Diana DeGette who received 73.8% of the vote and 272,892 number of votes
        
## Challenge Overview
Additional information had been requested by the election commission regarding the turnout at participating counties in the     region.  This analysis included the turnout for each county, percentage of votes per county and which county had the highest  turnout.

## Challenge Summary
  The results for each county participation in the election is as follows.
      Jefferson had 10.5% of the total vote for a total of 38,855 votes
      Denver had 82.8% of the total vote for a total of 306,055
      Arapahoe had 6.7% of the total vote for a total of 24,801
  
The county with the highest turnout was Denver with 306,055 votes or a total of 82.8%

This script could be used for any election which sorts data by BallotID, COunty and Candidate with identical analysis provided.  It could be modicied to provide analysis based on different available dimension as required.

