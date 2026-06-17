# AetherisWallet Security

AetherisWallet is designed around the principle that **you and only you** control your funds. This means we never have access to your keys, your balance, or your personal information.

---

## Security Model

### 1. Non-Custodial (Self-Custody)
AetherisWallet is a "non-custodial" wallet. Unlike an exchange (where they hold your keys), AetherisWallet generates your keys on your device and keeps them there. 
- **Benefit:** You cannot be censored or lose funds if a company goes bankrupt.
- **Responsibility:** You are responsible for backing up your 12-word phrase.

### 2. Local Encryption
Private keys are **never transmitted** over the network. All transaction signing happens locally on your device. Keys are encrypted using your device's secure hardware (Secure Enclave, Keystore, etc.).

### 3. SPV Architecture
AetherisWallet is a light client. It verifies transactions cryptographically without needing to download the entire blockchain or trust a central server for your balance.

---

## Privacy Features

### MWEB (MimbleWimble)
Optional confidential transactions that hide amounts and addresses. AetherisWallet supports MWEB on all platforms.

### Tor Routing
AetherisWallet can route its network connections through Tor, hiding your IP address from the nodes it communicates with.

---

## Open Source
AetherisWallet's source code is available on GitHub under the MIT License. This means:
- The code can be audited by anyone.
- There are no "backdoors."
- The project is community-driven.

---

## Reporting a Vulnerability
If you found a security issue in AetherisWallet, please report it via the GitHub Issues section of this repository.

---

## Read more
- **Backup Guide:** [how-to-backup.md](./how-to-backup.md)
- **Back to README:** [README.md](./README.md)
