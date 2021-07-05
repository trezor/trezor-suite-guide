# Send overview

Sending a transaction in Trezor Suite is easy. All you need is an account with a balance, and an address to send to. Other features shown in the Send form simply give you more control over the transaction.

## How to send a transaction

Sending a transaction is a straightforward process, but make sure you check all details are correct on your Trezor before confirming anything.  

1. The transaction recipient will provide you with an address. Copy this into the Address field.
2. Enter an amount to send. This can be denominated in fiat or crypto. Always check it is correct before proceeding.
3. Set a network fee. Preset amounts are calculated based on current network throughput. A custom amount can also be set. Trezor Suite will warn you if the fee is abnormally high, but you can check average fees for recent transactions online to set a reasonable price.
4. Click Review & Send, ensure all details shown on-screen are correct and the exact same address and amount are shown on your device.
5. Confirm the transaction on your Trezor and then click send in Trezor Suite.

### Fees

Network [transaction fees](transaction-fees.md) vary depending on how busy the network is. Trezor Suite estimates fees based on the priority of the transaction. These are Low, Economy, Normal, and High. Some networks only offer a custom fee.

Check network activity before sending a transaction to get an up-to-date idea of the fees being processed. You can use this information to set a Custom fee based on how quickly the transaction needs to confirm.

💡 Fees are only used to pay miners for adding transactions to the blockchain. They are not paid to Trezor or SatoshiLabs.

### Bitcoin address types

The address type you use for sending Bitcoin depends on the Account type you are using. By default, this will be a Native SegWit Bech32 account that creates addresses starting with the characters **`bc1`**.

Using a Native SegWit account is recommended as it helps keep transaction fees to a minimum. Addresses have changed over time as Bitcoin standards have evolved - a new address taproot address will be introduced with the Taproot upgrade in 2021.

You can tell what account an address is part of by the first characters:

* **Native SegWit** Bech32 addresses begin with **`bc1`**
* **SegWit P2SH** addresses begin with a **`3`**
* **Legacy P2PKH** addresses begin with a **`1`** 

 All account types are interoperable so it should not matter what type of address the recipient uses.

## How transactions work

Transactions are signed messages. When broadcast, they are added to a shared memory pool where other computers \(nodes\) can see them and the fee assigned to them. To claim the fee, the transaction has to be added into a block by a mining node.   

When you send a transaction, must be confirmed by the network by being mined into a block and then confirmed by successive block. An **unconfirmed transaction** is one that is in the memory pool waiting for confirmation. The time this takes depends on the fee you paid, from around ten minutes to many hours. 

### Speeding up a transaction with RBF

Every transaction you make creates multiple outputs. Some go to the recipient address, others are returned to a change address owned by you, the sender.

💡 Supported on BTC and ETH only

[Replace by fee \(RBF\)](rbf-replace-by-fee.md) is a special setting available on some cryptocurrency networks which lets you increase the fee used on any unconfirmed transaction and have it processed more quickly.

### Locktime for time-delayed transactions 

Once it has been picked up and mined into a block, at least six nodes must confirm it has been legitimately mined before it is considered confirmed.

💡 Supported on BTC only

[Locktime](locktime.md) is a feature available on some networks that delays the broadcasting of a transaction. This means that you can create and sign a transaction one day, and have it actually sent many hours, days or even years later.

