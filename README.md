# charitable fund dapp

## The donation project is managed with a dao

Each donation project include：
- contribute  
- Fund applicant

![image](https://user-images.githubusercontent.com/16698808/168980623-3a3073b6-6bdc-418d-b0fa-7930a3a081b5.png)

## Token：  
A type of the ERC20 token，for the voting authority of the donors，the more donations, the more token.    
## Governance:  
The following contracts are integrated：  
- Governor,
- GovernorCountingSimple,
- GovernorVotes,
- GovernorVotesQuorumFraction,
- GovernorTimelockControl  
https://docs.openzeppelin.com/contracts/4.x/api/governance
## Treasury：  
All donated funds pools, used for distributed funds to applicants (various token), all distributed funds should have a certain amount of voting, and the total amount is less than the total amount of funds in the pool.  
