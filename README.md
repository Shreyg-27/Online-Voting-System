# Online Voting System 

## Introduction

This project is an implementation of an Online Voting System using the basic concept of blockchain using python. The system allows registered voters to cast their votes securely and transparently. The blockchain ensures the integrity of the voting process and maintains a tamper-resistant record of all votes.

## Features

- **Blockchain-based Voting:** The system utilizes blockchain technology to store votes in a decentralized and immutable ledger.
  
- **Miner and Voter Roles:** Users can participate as either miners (block creators) or voters.

- **Registration of Voters and Miners:** The system supports the registration of voters and miners with unique identifiers.

- **Voting Process:** Voters can cast their votes for the nominees/parties of their choice.

- **Transaction Verification:** Each vote transaction is verified using PoW before adding it to the blockchain.

- **Chain Consensus:** The system implements a consensus algorithm to resolve conflicts and achieve agreement among different nodes in the network.

- **Visualization:** The system provides APIs to view the complete blockchain and individual blocks.

## Dependencies and Techstack

- Python 3.x
- Flask
- HTML


## Usage

### Miners

- Miners are responsible for adding new blocks to the blockchain through the mining process.
- To mine a new block, log in as a miner and click on the "Mine" button.
- The system will generate a new block and add it to the blockchain, provided that the proof of work is valid.

### Voters

- Voters can cast their votes for the nominated parties/candidates of their choice.
- To cast a vote, log in as a voter and select the party/candidate to vote for.
- Click on the "Vote" button to cast the vote.
- Once a voter has cast their vote, they will not be able to cast another vote.

### Full Chain

- The "Full Chain" API allows users to view the complete blockchain along with its length.

### Voting Process

1. Miners register their miner IDs by navigating to the home page and entering their unique ID.
2. Voters register their voter IDs by navigating to the "Voter" page and entering their unique ID.
3. Voters can view the current state of the blockchain by clicking on the "See Chain" button.
4. Voters can cast their votes by selecting their voter ID and choosing the party/candidate they wish to vote for.
5. After voting, the voter will be redirected to the "Repeat" page for verification.

### Results 

![image](https://github.com/Shreyg-27/Online-Voting-System/assets/98229024/5ff829d8-dcec-4b9c-a214-0c11e9eea7db)

![image](https://github.com/Shreyg-27/Online-Voting-System/assets/98229024/a6d8438c-bd3e-41ca-9389-e1642bd97505)

![image](https://github.com/Shreyg-27/Online-Voting-System/assets/98229024/bc35c9da-f217-4ad4-b12d-5ee618412518)

![image](https://github.com/Shreyg-27/Online-Voting-System/assets/98229024/d3d4c224-7b5d-46db-b7b4-abd2d2b4ee38)

![image](https://github.com/Shreyg-27/Online-Voting-System/assets/98229024/e76f0374-86c9-4dcb-9166-590e03cc7840)
