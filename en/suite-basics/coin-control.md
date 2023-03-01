# Coin Control

Coin Control allows you to take greater control of your Bitcoin assets while providing greater privacy when sending funds. It allows you to make a manual coin selection for an outgoing transaction, rather than relying on your wallet to make an automatic selection for you.

Normally, when sending Bitcoin, the “send from” address and “coin” (more specifically the unspent transaction output or UTXO) used as the input for sending are chosen automatically in Trezor Suite, with the aim of prioritizing older UTXOs and minimizing your transaction fees.

However, by using Coin Control to manually select which coins to spend, you are in full control of the addresses being used for a transaction and can avoid unwanted behavior, for example you can prevent mixing UTXOs that you don’t want to mix.

Your coin selection strategy must:

* Contain sufficient funds (i.e. the transaction amount)
* Cover the necessary transaction fees
* Ensure the transaction output is 546 sats or more (anything less than this is a “dust” output and you will end up overpaying on fees)

{% hint style="info" %}
The minimum value at which your Bitcoin (or other cryptocurrency) can be traded at is referred to as the **‘dust limit’**. Learn more about [dust & the dust limit](https://trezor.io/learn/a/dust-dust-limit) on the Trezor knowledge base&#x20;
{% endhint %}

It is strongly recommended that you label any incoming and outgoing coins, so that you can effectively manage your transaction history and identify the origin of coins.

### **Coin Control in Trezor Suite**

* Navigate to the Bitcoin account you want to spend from
* In the **Send** tab, complete the ‘Address’ and ‘Amount’ fields
* Click the **Coin Control** button to reveal your available UTXOs
* You can then manually select the UTXOs you want to spend
* Once you’re satisfied with your selection, click **Review & Send**
* Then confirm the transaction on your Trezor device as usual

Coin Control can be turned off at any time and Trezor Suite will revert to automatic selection of UTXOs. Turning off Coin Control will allow you to check the automatic selection of UTXOs.
