# Send overview

Sending a transaction in Trezor Suite is easy. All you need is an account with a balance, and an address to send to. Other features shown in the Send form simply give you more control over the transaction.

## How to send a transaction

The transaction recipient will provide you with an address. Copy this into the Address field.

Enter an amount to send as specified by the recipient. It can be denominated in fiat or crypto. Always double-check it is correct before proceeding.

Set a network fee. Preset amounts are calculated based on current network throughput. A custom amount can also be set.

Click Review & Send, ensure all details shown on-screen are correct and the exact same address and amount are shown on your device.

Confirm the transaction on your Trezor and then click send in Trezor Suite.



### Fees

Network fees vary depending on how busy the network is. This is reflected in the pre-calculated fee options \(Low, Economy, Normal, High\). It is recommended to check network activity before sending a transaction to get an up-to-date overview of what fees are currently being accepted, and set a Custom fee according to the priority of their transaction.

Fees are only used to pay miners for adding transactions to the blockchain. They are not paid to Trezor or SatoshiLabs.

### Address types

The address type you use for sending depends on the Account type you are using. By default, this will be a Bech32 native SegWit address beginning with the characters **bc1**. Using a native SegWit account is recommended as it helps keep transaction fees to a minimum.

Other address types can also be used, no matter the type of address your recipient is using.

## How transactions work

Every transaction you make creates multiple outputs. Some go to the recipient address, others are returned to a change address owned by you, the sender.

Once you have sent a transaction, it must be confirmed by the network. This takes time, proportional to the fee you paid, from ten minutes to many hours. An unconfirmed transaction sits in the memory pool waiting for confirmation. Once it has been picked up and mined into a block, at least six nodes must confirm it has been legitimately mined before it is considered confirmed.

