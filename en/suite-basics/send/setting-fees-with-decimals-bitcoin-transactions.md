# Setting fees with decimals (Bitcoin transactions)

When sending Bitcoin funds in Trezor Suite, users can now set non-integer custom fees to two decimal places.

To do so, in the **‘Fee’** section of the **‘Send’** transaction tab, simply select the **‘Custom’** fee option and enter the desired amount in sat/B, for example:

![](<../../../.gitbook/assets/image (3).png>)

💡 As shown in the example, fee rates are costed per byte of data, rather than the amount of Bitcoin being sent.

Transaction fees are collected by the miner who includes the transaction into the cryptocurrency public transaction ledger (blockchain). The size of the fee usually determines the transaction confirmation time, and transactions with a higher fee are likely to be confirmed faster, as miners will have a greater incentive to include profitable transactions in the blocks that they mine.

💡 If a very low (or no) fee is set, it is highly unlikely that the transaction will be mined. Also note that the lowest accepted fee rate by nodes is 1 sat/B.

Trezor Suite offers pre-calculated transaction fee sizes, and you can also use a service such as [mempool.space](https://mempool.space/) to check the recommended Bitcoin transaction fees when setting a custom amount.

If you’re unsure whether you’re setting a fee that’s high enough, make your transaction fee ‘replaceable’ by ensuring that **replace by fee (RBF)** is ON, so that you can ‘top up’ the fee even after sending the transaction.
