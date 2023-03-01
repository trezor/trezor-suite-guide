# Coinjoin fees

A **0.3% coordinator fee** will be taken from **fresh** **coins greater than 0.01 BTC.** This means that there is no such fee for UTXOs below 1,000,000 sats.

As with any other bitcoin transaction, you also need to pay **mining fees.** For coinjoin, you must pay a mining fee for **each round.**

These mining fees are what you normally pay when sending bitcoin from one address to another, as an incentive for miners to add transactions to the blockchain.

💡 Learn more about [transactions fees](https://trezor.io/learn/a/transaction-fees-in-trezor-suite-app) on the Trezor knowledge base.

Remixing is free, as well as coinjoining coins 1 hop from a previous coinjoin (although mining fees still apply). This means that when you receive coins from another coinjoin (1 hop) you will only pay the mining fee for the transaction, but not the coordinator fee. However, if a coin has more than 1 hop, the coordinator fee must be paid again.

💡 Outputs of less than 5,000 sats will be dropped.
