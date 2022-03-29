# Self-Hosted Full Node via Electrum Server

In the context of Bitcoin, a **node** is any computer that connects to the Bitcoin network. A node that fully validates transactions and blocks is referred to as a **full node.**

Full nodes verify transactions and blockchain rules by means of a locally built copy of the blockchain. They continually share new blocks and transactions, so that every node is updated to the latest state of the blockchain.

💡 **Full nodes** host and synchronize a copy of the whole Bitcoin blockchain, and are crucial for keeping the network functioning.

Data is shared via a peer-to-peer network, meaning each node is connected directly to several other nodes, ensuring there is no central authority running or controlling the blockchain.

Running a full node offers a number of advantages to users, such as the ability to interact with the Bitcoin network with greater privacy and security, and enabling users to prove ownership of their Bitcoin assets without relying on a third party.

By default, Trezor Suite determines Account balances by querying the Trezor Blockbook servers. However, users can now connect an Trezor Suite to their own full node, preserving the full privacy of their addresses and balances.

**How to use it in the Trezor Suite Desktop App**

💡 Note that you cannot connect to your own node via the Trezor Suite web app.

To enable the feature, you must access the Bitcoin advanced settings via:

* **Settings > Crypto > Bitcoin** ⚙️

In the **‘Backends’** pop-up window, you can switch from **‘Trezor servers (default)’** to **‘Custom Electrum server’** using the drop-down menu located at the top of the list of addresses.

The format of the example Electrum server address shown is:

* _“electrum.example.com:50001:t”_
* i.e., “Host:Port:Protocol”

In this field you should enter the Electrum server address running on your personal Bitcoin full node, then click on the **‘Confirm’** button.

In Suite you will now see the ‘**Backends’** icon in the top-right corner of the window, right next to the Privacy Mode icon.

Custom backend settings can be accessed through Bitcoin advanced settings, or by clicking on the Backends icon and selecting **‘Manage’.**

**Compatibility with Tor**

Users can also specify **“.onion”** addresses when defining their custom backends, enabling full compatibility with Tor in Trezor Suite. This helps avoid any potential privacy setbacks and ensures compatibility with out-of-the-box full node solutions that are _only_ accessible via an onion address.

💡 Tor is an integral part of the Trezor Suite **Desktop App.** Toggle Tor ‘on’ or ‘off’ using the **Tor switch** located in the top-right corner of the Trezor Suite window.

The process is very similar to that described above for non-onion addresses:

* Enable Tor using the **Tor Switch**
* Add your ‘.onion’ address(es) in the ‘**Backends**’ window, accessed via Bitcoin advanced settings
* Click ‘**Confirm**’

By using Tor, users can further enhance their privacy by obscuring their connection and having data encrypted at multiple levels.
