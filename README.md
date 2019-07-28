# Blockchain-Voting-System 

# Problem Statement
Current voting system is tedious, less transparent and there are always the chances of faults which leads to discrepancy between political parties regarding the results.
Therefore, our agenda is to implement a smooth and reliable voting mechanism which is suitable enough to overthrow the traditional methods and also to ensure the solution is fit and optimized enough for scaling in future.

# Solution
•	Our idea is to build a web application using Blockchain technology, creating a secure and transparent voting system.
•	This will make sure votes won’t be tampered or changed as editing a block on the blockchain will change the hash function of the block which will disturb the whole chain.
•	We are also creating a vote counting method allowing the results to be declared on the same date as well.

# Design 	
1.	Before the election day blockchain would be initialized. 
2.	On the election day the “cast your vote” button would be activated in the home page.
3.	The voters can visit any polling booth (anywhere in India). The election officials will take attendance using the usual methods and will do the physical verification. 
4.	Voter’s details will be added to system and after verification he/she will be allowed to cast his/her vote by selecting their preferred choice.
5.	After the election day “count all votes” button will be activated.
6.	Pressing this the user will be redirected to authentication page and then after verification the election authorities will be allowed to publish the results.

# Work Flow
1.	After voter’s authentication, the system will retrieve a token or key allowing the voter to vote exactly once.
2.	This whole process will maintain anonymity, the token will not trace back to the identity of the voter.
3.	The vote would be validated by the Proof of Authority Network and then a transaction ID will be given which would ensure that the vote has been appended successfully into the Blockchain database (each vote must be agreed upon by district nodes, where the voter is registered).
4.	Vote Counting: After elections have ended. Votes will be retrieved marked as unsealed and will be counted. This will make sure there is no double counting of votes. Security is ensured by the fact that every node on the blockchain has access to this information also and so can independently verify the final count. 

# Technology Stack
•	 Consortium blockchain (Azure Microsoft) 
•	 Rest APIs in C# language





