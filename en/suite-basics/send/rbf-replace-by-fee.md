# RBF (Replace by fee)

## Replace by fee

Replace by fee, or RBF, is a feature of the Bitcoin network that allows the sender of a transaction to set a condition that allows the transaction be replaced by another which is identical in all aspects but has a higher miner fee assigned to it. This can be done multiple times while the transaction is unconfirmed.

The benefits of RBF are that it allows you to gradually increase the fee until the transaction is accepted into a block. If the need to confirm a transaction becomes more urgent than initially thought, RBF also allows the sender to easily accelerate the transaction and have it added to the next block.

### Enabling and Disabling RBF

RBF is **enabled by default** in Trezor Suite. To turn it off, click on the RBF toggle before sending a transaction.

An RBF transaction is usually preferable to a non-RBF transaction to keep fees to a minimum.

Some recipients that accept unconfirmed transactions to provide faster service will not accept RBF. RBF **can be disabled** once a transaction has been sent, which is known as finalizing a transaction and is covered below.

### Bumping transaction fees

Increase the fee allocated to any unconfirmed RBF transaction by clicking Bump fee on the pending transaction in your Send tab.

A dialog will open that lets you assign a new fee, which must be higher than the previous one. Click Replace transaction and then confirm the action on your Trezor.

### Finalizing a transaction

Some merchants accept Bitcoin transactions without needing them to fully confirm, but only if the transaction is not replaceable.&#x20;

If you are dealing with such a merchant and your transaction is staying unconfirmed longer than expected, then instead of waiting for the transaction to confirm, you can Finalize it. This replaces the transaction with one that has RBF disabled and a final fee allocated to it. The fee cannot be increased any further once finalized, so set it appropriately.

### RBF by output reduction

When sending the maximum amount of bitcoin stored on a single account, there will be no leftover balance to increase the fee from. RBF by output reduction takes the additional fee from the amount being transferred, instead of the account balance.

Using RBF output reduction can be done in the same way as bumping the fee, as long as RBF was enabled when the transaction was sent.

1. To speed up confirmation times when sending the full balance of an account, click **Bump fee** on the pending transaction.
2. A new window will open where a new fee can be set.
3. Trezor Suite will show a message that there are no funds left for the fee, and that the amount sent must be reduced.
4. Set a new fee and confirm the new settings. The additional fee will then be reallocated from the transaction output.
