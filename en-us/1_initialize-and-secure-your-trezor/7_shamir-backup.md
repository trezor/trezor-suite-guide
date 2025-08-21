# Multi-share Backup

Trezor Model T, Safe 3 and Safe 5 users can use **Multi-share Backup** to protect their wallet backup (recovery seed) from loss or damage.

The Multi-share scheme entails generating multiple wordlists (**shares**) that must be combined to recover a wallet. Users set a recovery **threshold**, which represents the minimum number of shares required to recover a wallet: for example, in a **3-of-5** Multi-share Backup scheme, the user must combine **any three shares** in order to recover their wallet and funds. Any 'extra' shares serve as a backup in case the others are lost, stolen or damaged.

### Creating a Multi-share Backup

Depending on the state of your Trezor device, the process for creating a new Multi-share Backup varies:

#### I have a brand new Trezor:

If your Trezor is fresh out of the box, follow the on-screen instructions during device initialization to create a Multi-share Backup.

#### **I already have a** **Single-share Backup:**

* Connect and unlock your Trezor.
* In Trezor Suite, click on ⚙️ **Settings** in the left-hand side menu and go to the **Device** tab.
* In the **Wallet backup** section, click on **'Create Multi-share Backup'**.
* Follow the on-screen instructions for creating your Multi-share Backup.

#### **I have a different backup type e.g. 12-word, 24-word, Shamir backup (created before June 2024):**

If you're already using a different backup type, you must first wipe the device. **Make sure you keep your original backup safe,** so that you can access the associated wallets and funds if required.

Once you've wiped your Trezor, follow the on-screen instructions during device initialization to create a Multi-share Backup.

#### Quick step-by-step guide to Multi-share Backup:

* Set the total **number of shares** (i.e., the total number of individual wordlists).
* Set the **threshold** for recovery (i.e., the minimum number of shares that must be combined in order to recover your wallet and funds).
* **Write down all words** of each share **in order**, using a separate piece of paper for each share.
* Once complete, **secure each share** in a safe location isolated from the others.
* To recover your funds, you will need to collect as many shares as the threshold you set.

> 💡 Learn more about [Multi-share Backup](https://trezor.io/guides/backups-recovery/advanced-wallets/multi-share-backup-on-trezor) on the Trezor knowledge base
