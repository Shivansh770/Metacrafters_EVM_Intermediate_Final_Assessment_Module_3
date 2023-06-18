# Metacrafters_EVM_Intermediate_Final_Assessment_Module_3

# ERC20 CONTRACT USAGE AND OVERRIDE

This contract is for practicing erc20 smartcontract implementation through template to create new token and use other functions.

# Description
This contract has mint , burn, transfer , transferFrom and other funcions of erc20 contract.

After compilation to deploy the contract we need to pass following values (name of token), (Abre of token) and the Total supply we want for our token.

The mint funcion generates the total number of token for the account which is used to deploy the smartcontract.(Only Owner can mint tokens).

_Burn funcion burns corresponding account's token volume, Passed as parameters.

transfor funcion transfers specified number of tokens from owener account( account used to delploy smartcontract) to spefied account.

transferFrom funcion transfers specified number of tokens from one account to another account. I have overrided it as it was giving some kind of error so i just overrided it. So that it does what i want it to do.

# Executing the code

1.  goto ```https://www.openzeppelin.com/contracts``` website
2.  click (Open in Remix) Button.
3.  Copy my code from this repository and paste it on remix editor .
4.  Goto deploy section and give a token name , toke abre and the total supply of the token.
