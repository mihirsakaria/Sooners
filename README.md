# Sooners
WebApp for Code.fun.do++ by Team Sooners<br>
## Team Members

- <a href=" https://github.com/mihirsakaria">Mihir Sakaria</a>
- <a href="https://github.com/utpal58">Utpal Gupta</a>
- <a href="https://github.com/maasoomraj">Masoom Raj</a>

## Problem
In this fast growing world, we still stand in a queue for hours to apply for Voter-ID card. Also it take hours for us to cast our vote. Even sometimes, hooligans creates problem at polling booth and also tampers the EVM.<br>
The biggest problem faced by our Election Commission in today’s scenario is that some people cast vote by impersonating some other person, either dead or not present at the polling booth.
## Our Solution
We aim to build a web-app that would completely automate the process of voting in today’s world.<br>
On one side, we would maintain a database of citizens and their aadhar card details. And on the other side we would make the front end of website having 3 options, namely<br>
1.	Create Voter-ID card<br>
2.	Download e-Voter-ID card<br>
3.	Vote for your candidate<br><br>
Our aim is to link Voter-ID with the aadhar card (as this is compulsory for each citizen). In the database we will have an attribute of Voter-ID. At the time of creation of Voter-ID, it will be prompted to fill the necessary details, which should match the details corresponding in aadhar card. If the details are correct, we would create a hash using SHA256 corresponding to timestamp, aadhar card number, name etc. First 10 digits of hash created would correspond to the newly created Voter-ID number and would automatically be updated in the database. Then the details would be served as data of a block and uploaded to BlockChain 1(Voter-ID BlockChain)<br><br>
When we apply for downloading Voter-ID card, it would ask for details and if correctly filled, it would give you the copy of your data from the database and would act as one’s Voter-ID card.<br><br>
Now if one wants to vote, it will be prompted to fill in the necessary details. If correctly matched the citizen shall be allowed to vote. The vote and constituency of citizen will be served as data for Block and would be uploaded in BlockChain 2(Vote BlockChain).  
