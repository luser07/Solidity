# Solidity
CREATE TOKEN

Here I have created my own token and assigned tokens to different address. I also provided functions to update the tokens in address
such as deletion and addition of tokens.

DESCRIPTION

-> I began with the variables section, Declaring a Structure datatype(Coin) with 3 members that are pertinent to a typical token.
-> The second statement inside the contract is declaring the Structure variable 'coins' along with initialization with access specifier 'public'.
Thus variable 'coins' becomes a state variable.
->Next datatype address is mapped to datatype uint with access specifier 'public' and variable name balances.

-> Mint function
Mint function has 2 parameters 'address _add' and 'uint _val'. It also has a return datatype of uint.
The user is supposed to pass two arguments of the specified data type so that total supply of the coins and balances of the specified address gets added.
This function also returs the balance of the specified address.

-> Burn function
Burn function also has two parameters 'address _add' and 'uint _val'. It also has a return datatype of uint.
The user is supposed to pass two arguments of the specidied data type so that the total supply of the coins and balances of the specified address gets subtracted
from the current balances of both the total supply of the coins and the specified address's balance if and only if the value passed to the function parameter 
is less than or equal to the balancxe of the specified addeess.
This function also returns the balance of the specified address.


