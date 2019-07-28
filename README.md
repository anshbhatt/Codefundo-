CodeFundo++

Entities: Election Commission (EC), E-Voting Booth (VB), Candidates, Voters

-------------------------------------------------------------------------------------------------------------------------------------------
Pre Election:

Candidates register at the EC. The EC shall initiate a procedure for verification of the eligibility of the given candidate to contest for the required post.

Voters will register at the EC using a valid identity proof. The EC shall verify whether the voter is 18+ and not otherwise disqualified from voting. If the voter is eligible, the EC shall generate a unique Voter ID for the voter which must be preserved and not shared with anyone since it shall be used further during voting at the VB.

-------------------------------------------------------------------------------------------------------------------------------------------
During Election:

Voter will submit the unique Voter ID at the VB, which shall be authenticated via the database of the EC. If the Voter ID exists in the database and the voter has not placed a vote already, the voter shall be given a fifteen minute excess to the voting portal which shall have the candidates of the constituency of the voter. The agendas of the candidates shall be displayed along with their profiles. The voter shall now place a vote.

Once the vote is submitted, VB shall report to the EC and the EC shall store that, that particular voter has placed a vote. Hence, if the voter tries to vote for a second time, the VB shall initiate the authentication process, however the EC shall reject the attempt to vote. 

The anonimity of the voting process is maintained due to VB being a seperate entity than the EC. Randomly generated Voter IDs are used and hence no vote can be traced back to the voter. 

-------------------------------------------------------------------------------------------------------------------------------------------
Post Election:

The data of the number of votes each candidate obtained is available to the VB at each moment. however, the data shall be released only after the completion of the election so that it doesn't influence the unbiased nature of the election procedure. The final data shall be submitted to the EC within minutes of the completion of the election. The EC shall release the results.

-------------------------------------------------------------------------------------------------------------------------------------------
Use of Blockchain

After registration of candidates for the required post, a separate blockchain shall be created corresponding to each candidate. Whenever a voter places a vote correponding to any of the canidate, a new block corresponding to that particular blockchain shall be created. That block shall contain the time stamp, the voter Id and the total number of votes placed for that particular candidate as the data.
