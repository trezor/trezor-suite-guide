# Add a coinjoin account

{% hint style="info" %}
Trezor's third party coinjoin coordinator zkSNACKs will discontinue their service as of 1st June 2024. Coinjoin users do not need to move their private funds elsewhere, and all accounts will remain accessible after this date. Learn more on the [Trezor blog](https://blog.trezor.io/important-update-transitioning-from-coinjoin-in-trezor-suite-9dfc63d2662f).
{% endhint %}

#### Adding a coinjoin account in Trezor Suite:

* At the top of the **'My accounts'** menu bar, press the plus (➕) sign:

<figure><img src="../../../.gitbook/assets/Add-CJ-1.png" alt=""><figcaption></figcaption></figure>

* In the **'Account type'** drop-down menu, select **'Coinjoin account':**

<figure><img src="../../../.gitbook/assets/Add-CJ-2_new.png" alt=""><figcaption></figcaption></figure>

* Then select **'Add account'.**
* If you do not have Tor enabled, follow the prompt to **'Enable Tor':**

<figure><img src="../../../.gitbook/assets/Add-CJ-3.png" alt=""><figcaption></figcaption></figure>

Tor must be enabled for coinjoin to work. You can [learn more about Tor](https://trezor.io/learn/a/tor-in-trezor-suite-app) on the Trezor knowledge base.

Your Trezor will then ask you to allow access to your coinjoin account. Press the green check mark (✅) to confirm.

Trezor Suite will then run a coinjoin account discovery, **which may take significantly longer than regular account discovery**. After successful completion, your coinjoin account is ready to receive funds.

It is recommended to use a **minimum of 10,000 sats** for coinjoin. Ideally, the **total value** of your coinjoin input should be **1,000,000 sats or more,** otherwise coinjoin may be inefficient.

> 💡 Learn more about [coinjoin](https://trezor.io/learn/a/coinjoin-in-trezor-suite) on the Trezor knowledge base
