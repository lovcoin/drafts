# drafts_solidity
Drafts from smartcontracs and specifications to discuss for lovecoin projects.

lovecoin_reward_contract02.sol:

Use case:
Token holders can receive rewards that are bound to a ERC-20 token (see Constructor).
The Token-creator (or several DApps) can deposit profits to this reward-smart-contract.
The Token-holder can deposit his tokens in this SC and can later (see Constructor) withdraw 
his tokens plus the reward in ETH. 

Features of this Contract:
1) No gas-costs for token creator. Every user is self-responsible for receiving rewards by interacting with
   this smart contract.
2) compatible with any existing ERC-20 token.

 
