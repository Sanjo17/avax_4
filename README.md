
# DegenToken Smart Contract

This is a Solidity contract pertaining to the DegenToken, an ERC20 token that has been deployed onto the Avalanche network. This contract expands upon the capabilities of the OpenZeppelin `ERC20` and `Ownable` contracts, furnishing a range of functionalities including token minting, transferring, redeeming, burning, as well as the ability to verify token balances.

## Prerequisites

- Solidity Compiler (version ^0.8.18 recommended)
- Remix for testing


## Contract Details

- Contract Name: DegenToken
- Symbol: DGN

## Features

- Minting new tokens by the contract owner.
- Transferring tokens between accounts with an event emission.
- Redeeming tokens based on user input, with randomized item redemptions.
- Getting balance of user to know the amount of token the user has.
- Burning (destroying) tokens by the token owner.
- Event emission for token transfers, redemptions, and burns.
  

## License

This project is licensed under the MIT License. For details, see the [LICENSE](LICENSE) file.
