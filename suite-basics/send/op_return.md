# OP\_Return

OP\_Return is a bitcoin feature that provides a memo field for transactions. Usage of OP\_Return is limited to prevent network congestion.

💡 OP\_Return transactions make any bitcoin sent with the transaction unspendable. Do not send more than the bare minimum plus a network fee when creating an OP\_Return transaction.

#### How to send a message using OP\_Return

1. Create a transaction by entering a recipient address, amount and fee.
2. Select **Add OP Return** from the ellipsis drop-down menu.
3. Enter your memo into the left text box. On the right, your message will be shown in hexadecimal.
4. Click **Review & Send.** Confirm all details on your Trezor and finish the transaction.
5. Once confirmed, the hexadecimal data can be retrieved and decoded from the bitcoin blockchain.

{% hint style="info" %}
Learn more about [OP\_Return](https://trezor.io/learn/a/use-op\_return-in-trezor-suite-app) on the Trezor knowledge base
{% endhint %}
