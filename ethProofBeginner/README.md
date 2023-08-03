# macXtraCoin

A simple crypto token by malcolm Xtra

## Description

FUNCTIONALITY

tokens can be created to user addresses using mint
tokens can be destroyed from a given address using burn
you can check total supply at any moment using totalSupply
you can check token name using tokenName to get "macXtraCoin"
you can check token abbreviation using tokenAbbrv to get "MXC"

## Getting Started

GO TO REMIX IDE

CREATE A NEW FILE NAMED macXtra.sol

COPY AND PASTE THE CODE IN macXtra.sol (IN THIS DIRECTORY) INTO THE NEW FILE IN REMIX.

COMPILE THE CODE USING THE APPROPRIATE SOLIDITY VERSION

### Installing

DEPLOY TO REMIX VM FOR TESTING
CAN ALSO DEPLOY TO ANY EVM-COMPATIBLE BLOCKCHAIN OF YOUR CHOOSING BY CONNECTING YOUR METAMASK ACCOUNT TO REMIX

### Executing program

|Read Only function|input|output|
|----------------|---|-------|
|totalSupply||displays the total supply of MXC tokens at any moment|
|tokenName||displays "macXtraCoin", the token name|
|tokenAbbrv||displays "MXC", the token abbreviation|
|balances|address of user|returns balance of the given user address|


|function|inputs|effect|
|----------|-----|-------|
|mint|address, number of tokens| creates the number of tokens specified into the address provided|
|burn|address, number of tokens| destroys the number of tokens provided, deducting them from the balance of the address provided|





## Help

PROBLEMS WITH CODE:

ANY USER CAN MINT TOKENS
ANY USER COULD BURN TOKENS EVEN IF THAT USER DOESN'T OWN THEM

## Authors

malcolmXtra

with guidance from metaChris


## License

This project is licensed under the MIT license