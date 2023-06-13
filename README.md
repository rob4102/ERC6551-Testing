# ERC6551-Testing
Deploy Registry / Deploy Account Implementation / Deploy NFT contract or use existing NFT when creating an account. 
#
#
## Contract methods summary

The smart contract contains the following methods:

- `onERC721Received(address, address from, uint256 tokenId, bytes calldata)`: Handles an ERC721 token being received by this contract. Returns a selector.
- `receiveERC20(address from, address tokenAddress, uint256 amount)`: Receives an ERC20 token and stores the token info.
- `getERC20Balance(address tokenAddress)`: Returns the details of an ERC20 token held by the contract.
- `getNFTBalance(address owner)`: Returns the IDs of all NFTs owned by a specific address.
- `withdrawERC20(address tokenAddress, uint256 amount)`: Withdraws an ERC20 token from the contract.
- `withdrawNFT(address nftAddress, uint256 tokenId)`: Withdraws an NFT from the contract.
- `getContractBalance()`: Returns the balance of the contract.
