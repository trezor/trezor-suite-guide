# Dust & Dust Limit

**‘Dust’** is a term used to describe the tiny fractions of cryptocurrency that may remain after you have made a transaction.

Dust values are typically so small that they are (almost) entirely consumed by the transaction fee. This means tiny amounts of Bitcoin or other cryptocurrency can get ‘trapped’ in an address. Ideally, transactions will not create UTXOs of negligible value, and Trezor Suite takes care of this for you.

💡 The minimum value at which your Bitcoin (or other cryptocurrency) can be traded at is referred to as the **‘dust limit’.**

Dust may be cleaned up by performing manual coin selection via Coin Control, which lets users select specific coins (UTXOs) to spend in a transaction. By combining multiple tiny UTXOs, a larger transaction input can be created, which covers the transaction amount and fees. This technique is referred to as **'consolidation'.**

💡 Dust is a byproduct of transactions on most blockchains, and does not pose a serious financial risk.
