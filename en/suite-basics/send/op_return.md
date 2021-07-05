# OP\_RETURN

OP\_Return is a Bitcoin feature that provides a memo field for transactions. Usage of OP\_Return is limited to prevent network congestion.

⚠ OP\_Return transactions make any Bitcoin sent with the transaction unspendable. Do not send more than the bare minimum plus a network fee when creating an OP\_Return transaction.

Messages stored on the blockchain will be viewable as long as  Bitcoin exists and can not be censored.  

### How to send a message using OP\_Return

1. Create a transaction by entering a recipient address, amount and fee.
2. Select Add OP Return from the ellipsis dropdown menu.
3. Enter your memo into the left text box. On the right, your message will be shown in hexadecimal.
4. Click Review & Send. Confirm all details on your Trezor and finish the transaction.
5. Once confirmed, the hexadecimal data can be retrieved and decoded from Bitcoin's blockchain.

![](../../../.gitbook/assets/image%20%287%29.png)

