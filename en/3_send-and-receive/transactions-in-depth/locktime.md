# Locktime

Locktime creates a transaction that only broadcasts when a certain time or block height has been reached. Setting a locktime is as simple as stating a blockheight or Unix timestamp at which it should broadcast, and then signing the transaction as usual.

Broadcast is turned off by default when using locktime, meaning you will receive raw text data to broadcast from a node. If Broadcast is on, the transaction will be sent over the current network.

#### How to set a locktime

You can set a Locktime while creating a transaction:

1. Click **Add Locktime.**
2. Enter a block height or Unix timestamp when it should broadcast.
3. Set a fee.
4. Confirm transaction details on your Trezor.
5. You will be shown confirmation details.
6. Copy the data to your clipboard or save it as a text document. When Broadcasting (only after the block height has been reached) click Send instead.
7. Later, ideally from another network, use Send RAW or visit a block explorer to send the raw transaction data.

#### How to set a precise Locktime

Using block height to set a Locktime is not very accurate, as new blocks are mined on average once every 10 minutes, meaning around 144 blocks are mined per day. This number varies depending on the state of the network, and some blocks can take much longer to be mined.

Unix timestamps are used for more precise timing synchronized across computers. They track the number of seconds which have passed since January 1, 1970.

Use a [Unix timestamp converter](https://www.unixtimestamp.com/) to see the current timestamp and calculate a timestamp for a precise time in the future. Setting a Locktime is as simple as increasing the current timestamp by the number of seconds it should be delayed.

For example, if the current timestamp is 1625215800 and the desired Locktime is one week, the Unix timestamp to enter would be 1625820600 (the current timestamp plus one week, which is equivalent to 604800 seconds).

> 💡 Learn more about the [locktime feature](https://trezor.io/learn/a/locktime-in-trezor-suite-app) on the Trezor knowledge base
