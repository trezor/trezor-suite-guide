# Deposit stablecoins

You'll need USDC or USDT on Ethereum, plus a small amount of ETH in the same account to cover gas fees.

Depositing into a Morpho vault takes two separate on-chain transactions: first an approval (which authorizes the vault to use your stablecoins), then the deposit itself. You sign both on your Trezor device and pay gas on each. If you choose unlimited approval, future deposits of the same stablecoin skip the approval step.

1. Click **Earn** in the Trezor Suite sidebar and scroll to **Stablecoin yield**.
2. Find the vault you want (USDC or USDT) and click **Deposit now**.
3. Read the explainer and click **Continue**.
4. Accept the Terms of Use and Morpho's Disclaimer, then click **Confirm**.
5. Enter the amount you want to deposit, then click **Approve**.
6. Choose a spending limit (exact amount or unlimited) and click **Continue**.
7. Confirm the approval on your Trezor device and wait for it to settle on-chain.
8. Once the approval confirms, click **Deposit**.
9. Review the transaction simulation (shows your stablecoins leaving and the vault token you'll receive), then click **Confirm**.
10. Confirm the deposit on your Trezor device.

Your deposit is complete when you see the confirmation screen. Your stablecoins are now earning yield.

> 💡 Learn more about [Stablecoin Yield in Trezor Suite](https://trezor.io/guides/sending-receiving-staking-funds/interacting-with-smart-contracts/stablecoin-yield-in-trezor-suite) on the Trezor knowledge base
