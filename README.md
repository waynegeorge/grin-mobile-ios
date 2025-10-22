# Grin Mobile Wallet (iOS)

A simple yet stylish iOS wallet for the Grin cryptocurrency, built with SwiftUI (Wallet name TBD). Focuses on privacy and ease-of-use, connecting to a remote Grin node for lightweight performance.

## 🚀 Features
- **Secure Wallet Management**: BIP39 seed phrase generation and recovery.
- **Balance & History**: Real-time balance display and transaction log (cached offline).
- **Send & Receive**: QR code scanning/generation for slates; intuitive transaction flows.
- **Privacy-First**: Encrypted connections to remote node (Tor/HTTPS); no user data tracked.
- **Beautiful Design**: Clean SwiftUI interface with dark/light mode, smooth animations, and accessibility support.
- **MVP Scope**: Core wallet ops only — no exchanges or advanced analytics.

Future: Android port, multi-node support, fiat views.

## 🛠 Tech Stack
- **Language/UI**: Swift 5+, SwiftUI
- **Networking**: URLSession for secure HTTP/gRPC to remote Grin node
- **Crypto**: Custom slatepack handling (inspired by Grin RFCs); libsodium for encryption
- **Storage**: Keychain (secrets), Core Data (tx cache)
- **Dependencies**: 
  - Swift Package Manager: None external (minimalist approach)
- **Node**: Trusted Community nodes or remote full node (self-hosted; see [docs](https://github.com/mimblewimble/grin))

## 📱 Prerequisites
- macOS with Xcode 15+ (iOS 17+ target)
- iOS Simulator or physical device for testing
- Remote Grin node: Set up via [Grin Quickstart](https://github.com/mimblewimble/grin#quick-start). Configure Tor for anonymity.

## 🔧 Setup & Installation
1. **Clone the Repo**:
