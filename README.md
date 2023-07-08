# ETH_AVAX_Module3_Project
### ERC20 CONTRACT USAGE AND OVERRIDE
This contract is for practicing erc20 smartcontract implementation through template to create new token and use other funcions.
## Description
This contract has mint , burn, transfer , transferfrom and other funcions of erc20 contract. 

After compilation deploy the contract  

The mind funcion generates the totall number of token for the account which is used to deploy the smartcontract.(Only Owner can mind tokens).

_Burn funcion burns corresponding account's token volume, Passed as parameters.

transfor funcion transfers specified number of tokens from owener account( account used to delploy smartcontract) to spefied account.

transforfrom funcion transfers specified number of tokens from one account to another account. I have overrided it as it was giving some kind of error so i just overrided it. So that it does what i want it to do.

### Contract Functions

- `transfer(address recipient, uint amount)`: Transfers tokens from the caller's account to the recipient account.
- `approve(address spender, uint amount)`: Approves the spender to spend a certain amount of tokens on behalf of the caller.
- `transferFrom(address sender, address recipient, uint amount)`: Transfers tokens from the spender's account to the recipient account.
- `mint(uint amount)`: Mints new tokens and adds them to the owner's account (only callable by the contract owner).
- `burn(uint amount)`: Burns tokens from the caller's account.
- `totalSupply()`: Returns the total token supply.
- `balanceOf(address account)`: Returns the token balance of the specified account.
- `allowance(address owner, address spender)`: Returns the remaining allowance of tokens that the spender is allowed to spend on behalf of the owner.
