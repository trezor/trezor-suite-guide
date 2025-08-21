# Connect own node via Electrum server

**Full nodes** host and synchronize a copy of the whole Bitcoin blockchain, and are crucial for keeping the network functioning.

By default, Trezor Suite determines account balances by querying the Trezor Blockbook servers. However, users can now connect Trezor Suite (desktop app only) to their own full node, preserving the full privacy of their addresses and balances.

#### **How to use it in the Trezor Suite desktop app**

To enable the feature, you must access the Bitcoin advanced settings via:

* **Settings > Coins > Bitcoin** ⚙️

In the **Backends** window, switch from **Trezor servers (default)** to **Custom Electrum server** using the drop-down menu located at the top of the list of addresses.

The format of the example Electrum server address shown is:

* _“electrum.example.com:50001:t”_
* i.e., “Host:Port:Protocol”

In this field you should enter the Electrum server address running on your personal Bitcoin full node, then click on the **Confirm** button.

In Suite you will now see the **Backends** icon in the top-right corner of the window, right next to the Discreet Mode icon:

<figure><img src="../../../.gitbook/assets/Custom_Servers_Suite_Highlight.webp" alt=""><figcaption></figcaption></figure>

Custom backend settings can be accessed through Bitcoin advanced settings, or by clicking on the Backends icon and selecting **Manage.**

#### Compatibility with Tor

Users can also specify **“.onion”** addresses when defining their custom backends, enabling full compatibility with Tor in Trezor Suite. This helps avoid any potential privacy setbacks and ensures compatibility with out-of-the-box full node solutions that are _only_ accessible via an onion address.

The process is very similar to that described above for non-onion addresses:

* Enable Tor using the **Tor Switch**
* Add your ‘.onion’ address(es) in the **Backends** window, accessed via Bitcoin advanced settings
* Click **Confirm**

By using Tor, users can further enhance their privacy by obscuring their connection and having data encrypted at multiple levels.

> 💡 Learn more about [self-hosted full nodes](https://trezor.io/guides/trezor-suite/trezor-suite-desktop/full-node-via-electrum-server) on the Trezor knowledge base
