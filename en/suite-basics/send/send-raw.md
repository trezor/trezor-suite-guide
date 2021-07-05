# Send RAW

Sending a Raw transaction simply means broadcasting a transaction that has already been created and signed. This can be used with any transaction data that has been generated and signed but not Broadcast, including [Locktime](locktime.md) and [OP\_Return](op_return.md) transactions.

Create signed transaction data in the same way as Sending a normal transaction but with Broadcast off. Copy the signed data to a different machine and paste it through the Send RAW dropdown menu for privacy.

### Creating and broadcasting Raw transactions

To **create raw transaction data**:

1. Create a new transaction with Broadcast set to off.
2. Click on Sign.
3. Review all details on your Trezor and confirm that they correct.
4. Copy the signed transaction data or save it as a text document. Close the window.

To **send raw transaction data**:

💡 It is best to use a different host machine to send a signed raw transaction.

1. Select Send Raw from the dropdown menu.
2. Paste the raw transaction data into the text box.
3. Click Send.
4. The transaction will be broadcast and a confirmation will appear on screen.

