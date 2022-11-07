# Sign & Verify in Trezor Suite

The ability to sign a message with your bitcoin address — and securely verify the authenticity of such messages — makes it possible for you to prove ownership of a specific address, or ask someone else to prove that they own a specific address before you continue with a transaction.

Address ownership verification may also be requested if you lose access to an exchange account that was not set up using KYC documentation, or if you no longer have access to a two-factor authentication tool (e.g. mobile phone, email) that you use to access a Bitcoin exchange account.

### **How to sign a message in Trezor Suite**

* First, select **Accounts** at the top of the Suite window
* Then select the account in question using the **My accounts** sidebar menu
* From the menu bar at the top of the Account overview page, click the three dots to reveal the **Sign & Verify** tab:

![](../../../.gitbook/assets/SignVerify\_highlight.png)

* You will then see the **Sign/Verify message** window.
* Type the message into the **Message** box and select the correct address from the drop-down **Address** menu
* You can also toggle signature **Format** (Trezor or Electrum compatible)
* Then press ‘**Sign’**
* You will then need to confirm the signing operation on your Trezor device. If everything is correct, click ‘**Confirm’**
* Once confirmed using your Trezor, the signature will appear in the **Signature** box in Suite

### How to verify a message in Trezor Suite

* Select the account in question using the **My accounts** sidebar menu
* From the menu bar at the top of the Account overview page, click the three dots to reveal the **Sign & Verify.** Click on this to access the ‘**Sign/Verify message’** window
* Select the **Verify message** menu tab
* Copy the signed message into the **Message** box
* Then copy the address used for signing the message into the **Address** box
* Finally, copy the signature into the **Signature** box
* With all three fields completed, click on **‘Verify’**
* Follow the instructions on your Trezor screen to confirm the address and verified message
* You should then see **‘The signature is valid’** on your Trezor screen
* You can then click on **‘Verified’** to close the **Sign/Verify message** window
