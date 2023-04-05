# Accounts

Accounts let you create multiple isolated wallets on the same Trezor device, which are all derived from the same seed. This helps to keep your coins organized and improve your privacy.

#### Bitcoin accounts:

There are four types of bitcoin account supported by Trezor:

**Legacy**: creates addresses that **start with a 1**

**SegWit**: creates addresses that **start with a 3**

**Native SegWit**: creates addresses that **start with bc1q**

**Taproot**: creates addresses that **start with bc1p**

Trezor Suite uses Native SegWit (Bech32) addresses for Bitcoin by default. This type of address is generally the cheapest use, and is recommended for cross-compatibility with other account types.

#### Creating a new account

When you open Trezor Suite, an account will be created for each cryptocurrency enabled during device setup. Cryptocurrency preferences can be changed in **⚙️ Settings > Crypto** at any time.

Multiple accounts can be created for each cryptocurrency. You can create additional accounts to separate your funds, or manage them on one account using multiple addresses.

* To **create a new account**, click on the plus (+) icon at the top of the **My accounts** sidebar
* This will open the **New account** menu, where you can choose the type of account to create using the drop-down menu
* The new account can be the same type as an existing account as long as the first account has been used (i.e., you cannot create multiple empty accounts of the same type).

{% hint style="info" %}
Learn more about [managing accounts in Trezor Suite](https://trezor.io/learn/a/manage-accounts-in-trezor-suite-app) on the Trezor knowledge base
{% endhint %}
