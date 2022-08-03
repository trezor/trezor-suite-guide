# URI handlers

URIs (Uniform Resource Identifier) for Bitcoin and altcoins can be used to make payments with Trezor Suite. Introduced as part of [BIP-20](https://github.com/bitcoin/bips/blob/master/bip-0020.mediawiki) (now replaced by [BIP-21](https://github.com/bitcoin/bips/blob/master/bip-0021.mediawiki)), the URI scheme makes it easier for users to make Bitcoin payments either by clicking a link on a webpage or scanning a QR code. This functionality has also been extended to Bitcoin-like altcoins.

Bitcoin URIs follow the general format (although ‘**label’** and ‘**message’** are not yet supported in Trezor Suite):

`bitcoin:<address>[?amount=<amount>][?label=<label>][?message=<message>]`

**bitcoin:\<address>** must be specified, but the other fields in brackets are optional. An example of a Bitcoin URI specifying just the (receiving) address is:

`bitcoin:bc1qt0p5wwnw9kl6tknj43js3c2qe6kv7ayjjkjuha`

Payment amount may also be specified after the address, for example to request 2 BTC:

`bitcoin:bc1qt0p5wwnw9kl6tknj43js3c2qe6kv7ayjjkjuha?amount=2`

For bitcoin-like altcoins, the URI follows the same generic format. For example, the URI for a Dogecoin payment request of 3 DOGE would look like this:

`dogecoin:DJNpZTCtN3jAHxC3g4wtfnr9WtYbSN55U5?amount=3`

Custom altcoin URI handlers are compatible with the desktop version of Trezor Suite only, whereas Bitcoin URI handlers are compatible with both the web and desktop application.

To use the Trezor Suite web application as a URI handler, when you first start the application click on **‘Add application’** when prompted to add “[suite.trezor.io](http://suite.trezor.io)” as an app for handling Bitcoin links:

![](<../../.gitbook/assets/image (2).png>)

**Using URIs to make payments in Trezor Suite**

Clicking on a URI will auto-complete the **‘Send’** transaction fields using the details specified in the URI.

For example, if the URI is specified as:

`bitcoin:bc1qj89046x7zv6pm4n00qgqp505nvljnfp6xfznyw?amount=0.00001`

After clicking on the corresponding link in your browser, you will be asked to choose an application to open the link (you can also update your system preferences so that Trezor Suite is always used as the Bitcoin / Bitcoin-like altcoin URI handler):

![](<../../.gitbook/assets/image (9).png>)



Trezor Suite will then ask you to navigate to a suitable account from which you can send the requested funds:

![](<../../.gitbook/assets/image (5).png>)

Once you’ve selected the desired account, go to the **Send** tab, and the pop-up in Trezor Suite will then give you the option to **Autofill send form:**

![](<../../.gitbook/assets/image (1).png>)

After clicking on the Autofill button the input fields for the **Send** transaction will be populated accordingly, and you can then proceed by clicking **‘Review & Send’**:

![](<../../.gitbook/assets/image (1) (1).png>)
