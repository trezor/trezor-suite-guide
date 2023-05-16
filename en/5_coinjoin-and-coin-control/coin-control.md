# Coin control

Coin control lets you make a manual coin (or more specifically 'UTXO') selection for an outgoing transaction, rather than having Trezor Suite automate the selection for you. Manually selecting the funds you wish to spend in a transaction enhances privacy as you can avoid any unwanted behavior, e.g. mixing UTXOs that you want to keep separate.

Coin control can be turned off at any time, and Trezor Suite will revert to automatic selection of UTXOs.

Please note that your selection must comprise sufficient funds to cover both the transaction amount and the associated transaction fees.

#### **Coin Control in Trezor Suite**

* Navigate to the Bitcoin account you want to spend from.
* In the **Send** tab, complete the ‘Address’ and ‘Amount’ fields.
* Click the **Coin Control** button to reveal your available UTXOs.
* You can then manually select the UTXOs you want to spend.
* Once you’re satisfied with your selection, click **Review & Send.**
* Then confirm the transaction on your Trezor device as usual.

> LIGHTBULB Learn more about [Coin Control](https://trezor.io/learn/a/coin-control-in-trezor-suite) on the Trezor knowledge base
