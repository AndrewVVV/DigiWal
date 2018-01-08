[![Bread](/images/top-logo.jpg)](https://itunes.apple.com/app/breadwallet/id885251393)

## The easy and secure DigiByte wallet

DigiWallet for iOS is the best way to get started with digibyte. Our simple, streamlined design is easy for beginners, yet powerful enough for experienced users.

### Completely decentralized

Unlike other digibyte wallets, **DigiWallet for iOS** is a standalone digibyte client. It connects directly to the bitcoin network using [SPV](https://en.bitcoin.it/wiki/Thin_Client_Security#Header-Only_Clients) mode, and doesn't rely on servers that can be hacked or disabled. Even if Bread the company disappears, the app will continue to function, allowing users to access their money at any time.

### Cutting-edge security

**DigiWallet for iOS** utilizes AES hardware encryption, app sandboxing, and the latest iOS security features to protect users from malware, browser security holes, and even physical theft. Private keys are stored only in the secure enclave of the user's phone, inaccessible to anyone other than the user.

### Desgined with new users in mind

Simplicity and ease-of-use is **DigiWallet for iOS**'s core design principle. A simple recovery phrase (which we call a paper key) is all that is needed to restore the user's wallet if they ever lose or replace their device. **DigiWallet for iOS** is [deterministic](https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki), which means the user's balance and transaction history can be recovered just from the paper key.

![screenshots](/images/screenshots.jpg)

### Features

- [Simplified payment verification](https://github.com/bitcoin/bips/blob/master/bip-0037.mediawiki) for fast mobile performance
- No server to get hacked or go down
- Single paper key is all that's needed to backup your wallet
- Private keys never leave your device
- Save a memo for each transaction (off-chain)
- Supports importing [password protected](https://github.com/bitcoin/bips/blob/master/bip-0038.mediawiki) paper wallets
- Supports ["Payment protocol"](https://github.com/bitcoin/bips/blob/master/bip-0070.mediawiki) payee identity certification

### Localization

**DigiWallet for iOS** is available in the following languages:

- Chinese (Simplified and traditional)
- Danish
- Dutch
- English
- French
- German
- Italian
- Japanese
- Korean
- Portuguese
- Russian
- Spanish
- Swedish

We manage all translations with:

[PhraseApp - Start localizing software the simple way](https://phraseapp.com)

### WARNING:

***Installation on jailbroken devices is strongly discouraged.***

Any jailbreak app can grant itself access to every other app's keychain data. This means it can access your wallet and steal your bitcoin by self-signing as described [here](http://www.saurik.com/id/8) and including `<key>application-identifier</key><string>*</string>` in its .entitlements file.

---

**DigiByte Wallet for iOS** is open source and available under the terms of the MIT license.

Source code is available at https://github.com/Racecraft/digibytewallet-ios
