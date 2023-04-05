# Send RAW

Sending a Raw transaction simply means broadcasting a transaction that has already been created and signed. This can be used with any transaction data that has been generated and signed but not broadcast, including Locktime and OP\_Return transactions.

#### Creating and broadcasting RAW transactions

To create raw transaction data:

1. Create a new transaction with **Broadcast** set to **off.**
2. Click on **Sign.**
3. Review all details on your Trezor and **confirm** that they correct.
4. **Copy** the signed transaction data or save it as a text document. Close the window.

To **send raw transaction data:**

💡 It is best to use a different host machine to send a signed raw transaction.

1. Select **Send Raw** from the ellipsis drop-down menu.&#x20;
2. **Paste** the raw transaction data into the text box.
3. Click **Send.**
4. The transaction will be broadcast and a confirmation will appear on screen.

{% hint style="info" %}
Learn more about [sending crypto](https://trezor.io/learn/a/send-crypto-in-trezor-suite-app) on the Trezor knowledge base
{% endhint %}
