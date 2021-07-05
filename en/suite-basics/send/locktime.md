# Locktime

**Locktime** is an optLocktime creates a transaction that only broadcasts when a certain time or block height has been reached. Setting a locktime is as simple as stating a blockheight or Unix timestamp at which it should broadcast and then signing the transaction as usual.

### Why use Locktime?

* Transactions can be prepared in advance and sent at a certain time.
* Locktime further improves privacy when Broadcast over a different network.
* Transactions can be created that will send funds to another address if the transaction is not replaced by a certain time, acting as a dead man's switch.

### Setting a Locktime

You can set a Locktime while creating a transaction.

1. Click Add Locktime

   ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/101b3846-e30f-440f-ab8f-026372fa6f3a/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/101b3846-e30f-440f-ab8f-026372fa6f3a/Untitled.png)

2. Enter a block height or Unix timestamp when it should broadcast.

![](../../../.gitbook/assets/image%20%2813%29.png)

💡 Broadcast is turned off by default, meaning you will receive raw text data to broadcast from a node. If Broadcast is on, the transaction will be sent over the connected network.

1. Set a fee.
2. Confirm transaction details on your Trezor.
3. You will be shown confirmation details.

![](../../../.gitbook/assets/image%20%286%29.png)

1. Copy the data or save it as a text document. If Broadcast is on, just click Send.
2. Later, from another network, use [Send RAW](send-raw.md) or visit a block explorer to send the raw transactions data, such as [btc1.trezor.io/sendtx](https://btc1.trezor.io/sendtx).

![](../../../.gitbook/assets/image%20%2810%29.png)

### How to set a precise Locktime

Using block height to set a Locktime is not very accurate as new blocks are mined on average once every 10 minutes, meaning around 144 blocks mined per day. This number varies depending on the state of the network, and some blocks can take much longer to be mined.

Unix timestamps are used for more precise timing synchronized across computers. They track the number of seconds which have passed since January 1, 1970.

Use a [Unix timestamp converter](https://www.unixtimestamp.com/) to see the current timestamp and calculate a timestamp for a precise time in the future. Setting a Locktime is as simple as increasing the current timestamp by the number of seconds it should be delayed.

For example, if the current timestamp is 1625215800 and the desired Locktime is one week, the Unix timestamp to enter would be 1625820600 \(the current timestamp plus one week, or 604800 seconds\).

![](../../../.gitbook/assets/image%20%284%29.png)

### When to use Locktime

Locktime can **preserve privacy** by letting you sign your transaction, copy the signed data to a memory stick, and broadcast it from a public location so you don't reveal your IP address or other identifying data.

Locktime can also be used to set funds to transfer if no action is taken by the user. This could be useful for easy **inheritance planning** for cryptocurrency: send a transaction to an address owned by your next of kin with Locktime set for one year. If you are still alive and well when the transaction is due to be sent, resend the same transaction but extend the Locktime by one more year.ional part of Bitcoin [transactions](https://wiki.trezor.io/Transaction). It sets the earliest time a transaction can be mined into a block. It is possible to use locktime with [Trezor](https://wiki.trezor.io/Trezor) to make sure that a transaction is locked until a specific block height or a point in time.

