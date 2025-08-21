# Transaction fees

Transaction fees vary depending on the network used and conditions at the time. Miners, validators, and other forms of producing and verifying blocks will usually prioritize transactions with the highest fee.

Transaction fees are part of the network mechanism; they are not paid to SatoshiLabs.

#### Setting the right fee for a transaction

Choose an appropriate fee by deciding the priority of the transaction. Trezor Suite suggests fees based on the estimated time it will confirm in. The quickest bitcoin transaction it will usually confirm is 10 minutes.

The estimated time shown is reflective of **current conditions** in the mempool and assumes **standard block times**. This means that estimates should be correct at the time of sending but the transaction may arrive earlier or later than estimates due to those two variables.

To set a custom fee, simply click the Custom button and enter a fee. This is useful if you want to set very low fees, but be careful not to set them too high.

#### Speed up a slow or stuck transaction

If your bitcoin or litecoin transaction is taking too long to confirm you can bump the fee higher to make miners prioritize it. This is only possible if you did not turn off **replace-by-fee** (RBF) when the transaction was sent.

> 💡 Learn more about [transaction fees](https://trezor.io/guides/trezor-suite/trezor-suite-desktop/transaction-fees-in-trezor-suite) on the Trezor knowledge base
