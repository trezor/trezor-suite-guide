# Shamir Backup

While this feature is not found in device settings, Trezor Model T users can use Shamir backup to protect their recovery seed from loss or damage.

Shamir backup creates multiple shares instead of a single seed. Users can set a threshold of shares required to recover their wallet. The extra shares are a backup in case some of the others are lost, stolen or damaged.

#### Creating a Shamir backup

To create a Shamir backup on a used Trezor Model T, the memory must be wiped. **Make sure you have your recovery seed safely backed up** for any wallet already loaded on the device.

* With a new or wiped Trezor Model T, follow the Onboarding to create a Shamir share backup; alternatively, visit ⚙️ Settings > Device and choose Create backup.
* Set a total number of shares.
* Set a threshold for recovery.
* Write down all words of each share in order, using a separate piece of paper for each share.
* Once complete, secure each share in a safe location isolated from the others.
* To recover your funds, you will need to collect as many shares as the threshold you set.

{% hint style="info" %}
Learn more about [Shamir backup](https://trezor.io/learn/a/what-is-shamir-backup) on the Trezor knowledge base
{% endhint %}
