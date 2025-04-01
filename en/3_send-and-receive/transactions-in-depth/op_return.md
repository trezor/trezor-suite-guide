# OP\_RETURN

OP\_RETURN is a bitcoin feature that provides a memo field for transactions. Usage of OP\_RETURN is limited to one 80 byte message per transaction to prevent network congestion.

Messages stored on the blockchain can not be censored, and will be viewable as long as Bitcoin exists.

#### How to send a message using OP\_RETURN

1. Create a transaction by entering a recipient address, amount and fee.
2. Select **Add OP\_RETURN** from the ellipsis drop-down menu.
3. Enter your memo into the left text box. On the right, your message will be shown in hexadecimal.
4. Click **Review & send.** Confirm all details on your Trezor and finish the transaction.
5. Once confirmed, the hexadecimal data can be retrieved and decoded from the bitcoin blockchain.

> 💡 Learn more about [OP\_RETURN](https://trezor.io/learn/a/use-op_return-in-trezor-suite) on the Trezor knowledge base
