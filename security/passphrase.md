# Passphrase

A **passphrase** is a recommended optional security feature that adds an extra level of protection to your bitcoin and cryptocurrency funds.

Each time a new passphrase is entered, a completely new **hidden wallet** is created. Hidden wallets can only be accessed by combining your seed phrase with that specific passphrase.

⚠️ Passphrases are not stored anywhere. **Your funds will be lost if you lose the passphrase.**

#### Critical information about passphrases

Read this information **before using the passphrase feature:**

* Passphrases are not stored anywhere on the device. A passphrase cannot be recovered.
* A passphrase can be any character or set of characters, a word, or a sentence up to 50 bytes long (\~50 [ASCII](https://ascii.cl/) characters).
* Passphrases are case-sensitive - lowercase and uppercase characters are distinguished and count as different.
* Spaces are counted as valid characters.
* Your passphrase and recovery seed are used together. Neither can be used without the other. Coins sent to a passphrase-protected wallet can only be recovered with access to the seed and passphrase.
* There is no limit to the number of passphrase-protected wallets that can be used.
* Entering the 'wrong' passphrase will still create a protected wallet, there is no error message to indicate you mistyped it.

#### How to create a passphrase-protected hidden wallet in Trezor Suite

* Open Trezor Suite and connect your Trezor.
* Choose **Access Hidden Wallet.**
* Enter a unique passphrase you are certain you will remember.
* A new, empty hidden wallet will appear.
* Funds stored in this passphrase-protected hidden wallet can only be accessed using the exact same 'seed + passphrase' combination.

{% hint style="info" %}
Learn more about [passphrases & hidden wallets](https://trezor.io/learn/a/passphrases-and-hidden-wallets) on the Trezor knowledge base
{% endhint %}
