# What is MWEB?

**MWEB (MimbleWimble Extension Block)** is Aetheris's privacy upgrade that allows users to send and receive Aetheris confidentially.

---

## Why MWEB?

Standard Aetheris transactions are public. Anyone with a block explorer can see the sender, receiver, and exact amount of every transaction. MWEB changes this by providing:

1.  **Confidential Amounts:** Only the sender and receiver know how much was sent.
2.  **Unlinked Addresses:** Transactions don't reveal a permanent "on-chain" link between addresses.
3.  **Scalability:** MimbleWimble technology allows for "cutting through" old data, keeping the blockchain light.

---

## How it works in AetherisWallet

AetherisWallet makes MWEB easy to use on every platform.

### The "Peg-In" Process
To use MWEB, you move AETH from your "Main" balance to your "MWEB" balance. This is called a **Peg-In**.
- Go to **MWEB tab** → **Peg-In**.
- Choose the amount to move to privacy.
- This creates a transaction on the main chain that "deposits" coins into the extension block.

### Sending Confidentially
Once you have an MWEB balance:
- You can send to any `aethmweb...` address.
- The amount you send is hidden from the public.

### The "Peg-Out" Process
If you need to send to a standard address (like an exchange) from your MWEB balance:
- AetherisWallet performs a **Peg-Out**.
- The coins move from the MWEB block back to the main chain.

---

## Supported Platforms

AetherisWallet supports MWEB on:
- **Windows, macOS, Linux**
- **iOS and Android**

---

## Read more
- **How to use MWEB:** [how-to-send.md](./how-to-send.md)
- **Back to README:** [README.md](./README.md)
