# Passphrase\*

A passphrase functions like an extra word added to your recovery seed. Each unique combination of recovery seed + passphrase grants access to the corresponding, unique **hidden wallet.** Passphrases are not stored on your Trezor, and using a strong passphrase means your coins are extra safe.

{% hint style="warning" %}
**If you forget a passphrase, you lose access to any associated funds.** Only use the feature once you understand how it works.
{% endhint %}

#### Create a passphrase-protected hidden wallet in Trezor Suite

When you start Trezor Suite and connect your device, you will see the **'Select wallet type'** modal window:

<figure><img src="../.gitbook/assets/Select_wallet_type-modal.png" alt=""><figcaption></figcaption></figure>

* Type your memorable passphrase into the _'Enter passphrase'_ input field.
* Confirm the passphrase using your Trezor device.
* Trezor Suite then runs the coin discovery process to find your accounts and balances; if the hidden wallet is empty, you must then type the same passphrase in the **'Confirm empty hidden wallet'** modal window and confirm it using your Trezor.

Hidden wallets can be loaded at any time by clicking on the device button in the top-left corner of the Suite interface, selecting **'+ Add wallet',** and then typing in the _exact_ passphrase.

{% hint style="info" %}
Learn more about [passphrases and hidden wallets](https://trezor.io/learn/a/passphrases-and-hidden-wallets) on the Trezor knowledge base.
{% endhint %}
