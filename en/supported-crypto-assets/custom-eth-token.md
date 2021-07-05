# Custom ERC20 Token

ERC20 tokens are supported natively by Trezor hardware wallets and Trezor Suite. Send ERC20 tokens to any Ethereum address you own and they will be findable in Trezor Suite.

Other token networks are not supported by Trezor hardware wallets or Suite at this time.

### How to store custom tokens

Create a new Ethereum address through an Ethereum [Account](https://www.notion.so/Accounts-60adc181cc424c90877650768cb8053d) and send the token to that address.

Once a token is received at that address, you can keep track of it by adding its Contract Address to Suite:

1. Go to your Ethereum account and switch to the Tokens tab.  
2. Click on the Add token button or select Add token from the dropdown ellipses menu.
3. You will be asked for the token contract address, which will find the token and add it to your assets.
4. Tokens usually list their contract address on the official project website but they can also be found using Ethereum block explorers such as [Etherscan](https://etherscan.io/).
5. Once your first token has been added, you can continue to add more through the dropdown menu.

#### Using Etherscan to find a token's contract address

If you do not know the contract address of the token you want to add, you can try searching for it on [Etherscan](https://etherscan.io/) by following these steps:

1. In the search bar, type the ticker for your coin e.g. ZRX for 0x or UNI for Uniswap.
2. Make sure you are clicking on the correct one as multiple tokens can use the same ticker.
3. You will see the contract address on the right-hand side.
4. Double check the address against the token project's official site and make sure it is the correct address, as some tokens may use multiple smart contracts.

Generally the contract address you are looking for will be shown alongside the supply, price, and other information. Contracts that are used for functionality alone will generally not show that information.

