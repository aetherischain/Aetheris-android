# How to send Aetheris from AetherisWallet

Sending Aetheris from AetherisWallet takes under a minute once you understand the basic flow. This guide covers standard sends and MWEB confidential sends.

---

## 1. Open the Send screen
On the main wallet dashboard, tap the **Send** button.

## 2. Enter the recipient address
You have three ways to provide an address:
- **Scan QR code:** Tap the QR icon to open your camera.
- **Paste:** Tap the paste button if you have an address on your clipboard.
- **Manual entry:** Type or paste the address directly into the field.

> 💡 **Tip:** AetherisWallet automatically detects if the address is a standard Aetheris address (starts with `A`, `E`, or `aeth1`) or an MWEB address (starts with `aethmweb`).

## 3. Enter the amount
Type the amount in AETH. AetherisWallet shows:
- The equivalent in your local fiat currency (USD, EUR, etc.)
- Your total available balance.

## 4. Review details
AetherisWallet shows a confirmation screen with:
- **Recipient address**
- **Amount**
- **Estimated network fee**
- **Expected confirmation time**

## 5. Send and confirm
Tap **Confirm and Send**. You will be asked for your device PIN, biometric (FaceID/TouchID), or wallet password.

AetherisWallet signs the transaction locally and broadcasts it to the Aetheris network.

---

## Sending with MWEB (Confidential)

To send a confidential transaction, the recipient must provide an **MWEB address** (starting with `aethmweb`).

1. Make sure you have a MWEB balance (peg-in first if you don't — see [What is MWEB?](./what-is-mweb.md)).
2. Paste the `aethmweb` address.
3. AetherisWallet will automatically use MWEB for the send.
4. Your amount and change will be hidden from the public blockchain.

---

## Troubleshooting

### Why is my transaction "Pending"?
Aetheris blocks occur every 2.5 minutes on average. Your transaction needs at least 1 confirmation to be considered "sent" and usually 6 for "completed."

### Fees are too high?
AetherisWallet estimates fees automatically based on current network conditions. Typical Aetheris network fees are very low (often <$0.01).

---

## Read more
- **How to receive:** Use the Receive tab in the app.
- **What is MWEB?** [what-is-mweb.md](./what-is-mweb.md)
- **Back to README:** [README.md](./README.md)
