# RBF \(Replace by fee\)

## Replace by fee

Replace by fee, or RBF, is a feature of the Bitcoin network that allows the sender of a transaction to set a condition that allows the transaction be replaced by another which is identical in all aspects but has a higher miner fee assigned to it. This can be done multiple times while the transaction is unconfirmed.

The benefits of RBF are that it allows you to gradually increase the fee until the transaction is accepted into a block. If the need to confirm a transaction becomes more urgent than initially thought, RBF also allows the sender to easily accelerate the transaction and have it added to the next block.

### Enabling and Disabling RBF

RBF is **enabled by default** in Trezor Suite. To turn it off, click on the RBF toggle before sending a transaction.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d6121708-a83c-4fce-b651-5f5f152edc33/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d6121708-a83c-4fce-b651-5f5f152edc33/Untitled.png)

An RBF transaction is usually preferable to a non-RBF transaction to keep fees to a minimum.

Some recipients that accept unconfirmed transactions to provide faster service will not accept RBF.

RBF can also be disabled once a transaction has been sent - this is known as finalizing a transaction, covered in the section below.

### Bumping transaction fees

Increase the fee allocated to any unconfirmed RBF transaction by clicking Bump fee on the pending transaction in your Send tab.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bc569570-8252-4273-9507-6f65d168a49b/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bc569570-8252-4273-9507-6f65d168a49b/Untitled.png)

A dialog will open that lets you assign a new fee, which must be higher than the previous one. Click Replace transaction and then confirm the action on your Trezor.

### Finalizing a transaction

If you have sent an RBF transaction and it stays unconfirmed longer than expected, the recipient may not accept RBF transactions.

Instead of waiting for the transaction to fail, you can finalize the transaction. This overrides the transaction with one that has RBF disabled and a final fee allocated to it. The fee cannot be increased any further, so set it appropriately.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c553bee2-4ca0-462c-a7cf-dde99add8412/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c553bee2-4ca0-462c-a7cf-dde99add8412/Untitled.png)

