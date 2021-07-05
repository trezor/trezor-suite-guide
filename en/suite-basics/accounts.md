# Accounts

Accounts let you create multiple isolated wallets on the same Trezor device, derived from the same seed, to keep your coins organized and improve privacy.

### Creating a new account

When you open Trezor Suite, you'll see an account for any enabled coins. You can use these accounts and send all of your coins to the addresses they creates, or you can create more accounts to separate your funds.

To **create a new account**, click on the plus \(+\) icon at the top of the accounts sidebar. This will open a window where you can choose the type of account to create. It can be the same type as an existing account.

### **Why create multiple accounts?**

Using different accounts for the same cryptocurrency means each account its own extended public key \(XPUB\). Once an XPUB is revealed, it allows people to look up transactions that have been made to and from all the addresses belonging to the account. For privacy, it is better to use different XPUBs for different purposes by managing multiple accounts. This is made easier by labeling accounts.

### Different types of account

There are three types of Bitcoin account supported by Trezor:

**Legacy**: creates addresses that **start with a 1** and use 148 vBytes

**SegWit**: creates addresses that **start with a 3** and use 91 vBytes

**Native SegWit**: creates addresses that **start with bc1** and use 68 vBytes.

Native SegWit is generally the cheapest address to use. While addresses should be cross-compatible in most cases, **some older services will not allow you to send Bitcoin from Native SegWit addresses.** If this is the case, send your coins to a SegWit address by creating a new account and then use the service.

### **Use Accounts to manage XPUBs**

You can view your extended public key \(XPUB\) on the account's main page by switching to the Account details tab. Every account has its own unique XPUB, which makes it possible to see transactions going to and from the account. This is used to create 'watch-only' wallets that link all past, current, and future addresses used by the selected account. 

While you can share this information in some scenarios, we recommend keeping it secret as it presents a privacy concern where others can view your balances and activity.

