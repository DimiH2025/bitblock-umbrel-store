# Bit-Block Umbrel Community App Store

An Umbrel community app store for [Bit-Block](https://github.com/DimiH2025/Bit-Block), a Bitcoin full node with a GUI and local anti-spam relay policy. The app runs the node together with the [OCEAN DATUM gateway](https://github.com/OCEAN-xyz/datum_gateway), so a home miner can mine on block templates built by their own node.

## Apps

| App | Description |
|-----|-------------|
| **Bit-Block + DATUM** | Bit-Block V4 full node plus the DATUM gateway and its dashboard |

## Install

1. Open your Umbrel in a browser and go to the **App Store**.
2. Open the menu at the top right and choose **Community App Stores**.
3. Paste this link and click **Add**:
   `https://github.com/DimiH2025/bitblock-umbrel-store`
4. Open the new store, select **Bit-Block + DATUM** and click **Install**.

## Using it

- Open the app and sign in to the DATUM dashboard. The password is shown on the app's page in Umbrel.
- Enter your payout address in the dashboard.
- Point your miner at `stratum+tcp://<your Umbrel address>:23334` with any worker name.

## Good to know

- The first start downloads the whole Bitcoin blockchain. It needs a large SSD and takes days.
- The node cannot run pruned, because DATUM needs the transaction index.
- Do not run it together with the Bitcoin Node app. Both use the same network ports.
- This is a test release. Mining at home is a lottery: one rig has a very small chance of finding a block.

## Links

- Bit-Block: https://github.com/DimiH2025/Bit-Block
- Report problems: https://github.com/DimiH2025/Bit-Block/issues
