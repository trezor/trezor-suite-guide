# Accounts

Accounts let you create multiple isolated wallets on the same Trezor device, derived from the same seed, to keep your coins organized and improve privacy.

### Creating a new account

When you open Trezor Suite, an account will be created for each enabled cryptocurrency. Visit Coin Settings to enable or disable them.&#x20;

Multiple accounts can be created for each cryptocurrency. You can create more accounts to separate your funds or manage them on one account using multiple addresses.

To **create a new account**, click on the plus (+) icon at the top of the sidebar. This will open a menu where you can choose the type of account to create. It can be the same type as an existing account as long as the first account has been used.

### **Why create multiple accounts?**

Using different accounts for the same cryptocurrency means each account its own extended public key (XPUB). Once an XPUB is revealed, it allows people to look up transactions that have been made to and from all the addresses belonging to the account. For privacy, it is better to use different XPUBs for different purposes by managing multiple accounts. This is made easier by labeling accounts.

### Different types of account

There are four types of Bitcoin account supported by Trezor:

**Legacy**: creates addresses that **start with a 1** and use 148 vBytes

**SegWit**: creates addresses that **start with a 3** and use 91 vBytes

**Native SegWit**: creates addresses that **start with bc1q** and use 68 vBytes

**Taproot**: creates addresses that **start with bc1p** and use 57.5 vBytes

(In each case, the address size relates to spending a UTXO of the given type).

Trezor Suite uses Native SegWit (Bech32) addresses for Bitcoin by default. This type of address is generally the cheapest use, and is recommended for cross-compatibility with other account types.

Taproot improves how transactions are signed and allows transaction data to be handled more efficiently. The Taproot upgrade improves both privacy and network efficiency, making Bitcoin transactions safer. More complex transactions will be quicker to send, thanks to the fact that with Taproot, the wallet no longer needs to send the often extensive history of transactions which preceded the one being spent. Please note that **some older services will not allow you to send Bitcoin to Taproot addresses.**

### **Use Accounts to manage XPUBs**

You can view your extended public key (XPUB) on the account's main page by switching to the Account details tab. Every account has its own unique [XPUB](accounts.md#use-accounts-to-manage-xpubs), which makes it possible to see transactions going to and from the account. This is used to create 'watch-only' wallets that link all past, current, and future addresses used by the selected account.&#x20;

While you can share this information in some scenarios, we recommend keeping it secret as it presents a privacy concern where others can view your balances and activity.

## Taproot Accounts

Taproot represents the first major upgrade to Bitcoin since SegWit was implemented in 2017. It comprises three Bitcoin Improvement Protocols (BIPs), and will improve Bitcoin's functionality. Taproot improves both privacy and network efficiency, making Bitcoin transactions safer. More complex transactions will be quicker to send, thanks to the fact that with Taproot, the wallet no longer needs to send the often extensive history of transactions which preceded the one being spent.

The update comprises three different BIPs - namely [**BIP 340**](https://wiki.trezor.io/Taproot), [**BIP 341**](https://wiki.trezor.io/Taproot) and [**BIP 342**](https://wiki.trezor.io/Taproot)****

### **Using Taproot on your Trezor**

First, ensure that your Trezor is running Firmware version 2.4.3 or higher. If not, please [update](https://wiki.trezor.io/User\_manual:Updating\_the\_Trezor\_device\_firmware) the Firmware installed.

1. Open Trezor Suite and connect your Trezor device by following the on-screen instructions. Then navigate to '**My accounts**' in the sidebar menu, and click the '**+**' button
2. In the '**New Account**' window, select '**Bitcoin**'
3. Under '**Account type**' choose the '**Taproot**' option from the drop-down menu
4. Then click the '**Add Account**' button
