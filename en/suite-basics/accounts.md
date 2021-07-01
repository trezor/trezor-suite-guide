# Accounts

Accounts allow you to create multiple isolated wallets on the same device using the same seed, to keep your coins organized and improve privacy.

### Creating a new account

When you open Suite, you'll see an account named Bitcoin \#1. You can use this one account and send all of your coins to the addresses it creates, or you can create more accounts to separate your funds as a high-level form of coin control. By default, this account uses Native SegWit addresses \(also known as bech32 or SegWit v0\).

To create a new account, click on the plus \(+\) icon at the top of the accounts sidebar. This will open a window where you can choose the type of account to create. It can be the same type as an existing account.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b9d907e1-ee9e-43ff-a75d-7fdfde7eddc9/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b9d907e1-ee9e-43ff-a75d-7fdfde7eddc9/Untitled.png)

**There are 3 types of Bitcoin accounts supported by Trezor:**

**Legacy**: creates addresses that start with a 1 and use 148 vBytes

**SegWit**: creates addresses that start with a 3 and use 91 vBytes

Native SegWit: creates addresses that start with bc1 and use 68 vBytes, making it generally the cheapest type to use.

While addresses should be cross-compatible in most cases, **some older services will not allow you to send Bitcoin from Native SegWit addresses.** If this is the case, send your coins to a SegWit address by creating a new account and then use the service.

### **Why create a new account?**

The main benefit of using different accounts for the same cryptocurrency is that each account has its own extended public key \(XPUB\). Once an XPUB is revealed, it allows people to look up transactions that have been made to and from all the addresses that XPUB generated. For privacy, it is better to use different XPUBs for different purposes by creating a new account. This is made easier by labeling accounts.

### **What is an XPUB?**

You can view your Public key \(XPUB\) on the account's main page by switching to the Account details tab. This information is used to create a 'watch-only' wallet as it links all past, current, and future addresses used by the selected account. Other accounts have their own unique XPUB.

While you can share this information in some scenarios, we recommend keeping it secret as it presents a privacy concern where others can view your balances and activity.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fc06b02c-4042-4f95-ba04-113521b62ad4/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fc06b02c-4042-4f95-ba04-113521b62ad4/Untitled.png)

