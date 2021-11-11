## Deploy Simple ERC20 Token on Remix

### Deploy Token on Remix 

1. Compile and deploy contracts on JVM to check all is working well 

- Copy Token.sol Solidity Code into a file in Remix rename Token.sol
- Select Solidity Compiler Page
  - On Compiler Options dropdown select 0.8.6 version
  - Click "Compile Token.sol" button
- Select Deploy and Run Transactions Page
  - Environment dropdown select JavaScript VM
  - Accounts dropdwon -> pick any of the accounts in dropdown
- Deploy Button
  - Enter the parameters for deployment for (name, symbol, decimals,totalSupply) 
  - Example paramters "TokenName", "TKT", 18, 7000
  - Click deploy button
- Deployed Contracts
  - Scroll down to deployed contracts section and click on deployed contract
  - View buttons for all the functions you can carry out on contract e.g approve, transfer etc