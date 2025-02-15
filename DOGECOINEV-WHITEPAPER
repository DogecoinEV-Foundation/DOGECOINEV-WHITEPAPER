# DogecoinEV (DEV)

A high-speed, meme-friendly, **Layer 1 blockchain** optimized for big blocks, fren-to-fren transactions, and merge mining. Inspired by the best parts of **Dogecoin** and **Pepecoin**, DogecoinEV aims to bring fun, simplicity, and scalability back to crypto—fully in line with **Elon’s Vision** for a future where crypto is fast, inclusive, and unstoppable.

## Abstract

DogecoinEV (DEV) is not just another fork—it’s an evolution, a movement, a vision of what blockchain should be: fast, fun, and limitless. By increasing block size, leveraging merge mining, and embracing a truly decentralized ethos, DogecoinEV ensures that **everyone—yes, even normies—can be part of the future** while still appealing to seasoned veterans of the crypto space.

---

## Introduction

Think of DogecoinEV as **Dogecoin, but optimized for scale and speed.** We took what works, supercharged it, and now **DEV** is ready to send transactions at hyperspeed, fully aligning with Elon’s dream of a high-throughput meme-friendly chain.

### Quick Highlights
- **Bigger Blocks, More Data, More Fun** – 10MB blocks allow for more transactions, more memes, and more possibilities.
- **Prefix D** – Addresses start with **D**, preserving that iconic Dogecoin flair.
- **BIP Activation at Block 1k** – We’ve integrated BIP features early, ensuring our chain can evolve.
- **Fren-to-Fren (DEVS) Transactions** – A currency made for sharing, tipping, and having a good time.
- **Merge Mining** – Earn while mining Dogecoin and Litecoin at the same time, boosting security and efficiency.
- **One-Minute Block Times** – Because no one likes waiting. Instant feels, instant confirmations.
- **Scrypt Proof-of-Work** – Keeping mining decentralized, just how we like it.

DEV is built to scale, and designed to keep the original fun-loving spirit of Dogecoin alive—while taking it to the next level.

---

## Core Features

### Layer 1 Blockchain
DogecoinEV isn’t a token. **It’s the real deal.** A full-fledged, self-sustaining blockchain built for speed and efficiency.

### Scrypt Proof-of-Work
Mining should be fair, open, and rewarding. **DEV sticks with Scrypt**, meaning if you can mine Dogecoin, you can mine DogecoinEV.

### 10 MB Block Size – More Room for Transactions
Bigger blocks mean **more transactions, lower fees, and room for innovation.**
- Say goodbye to congestion.
- Say hello to **fren-speed transactions** that get confirmed fast.
- More space means **more possibilities**—from NFTs to decentralized applications.

### Merge Mining (AuxPoW) – Double the Rewards, Double the Fun
Activated at **block 30,000**, DEV allows you to mine DogecoinEV **alongside Dogecoin and Litecoin, with no extra effort.**

### Designed for Real People
- **Easy-to-Use Core Wallet:** Send and receive DEV with a click.
- **Low Fees:** No one likes paying extra, and with DEV’s efficient block structure, fees stay **stupid low.**
- **Fast Confirmations:** One-minute blocks keep everything moving **at meme speed.**

### Chain ID
- **DogecoinEV Chain ID:** `63`

### BIP Features Activated at Block 1000
To ensure the chain remains agile and upgradable, major Bitcoin Improvement Proposals (BIPs) were integrated and activated at **block 1,000**, allowing for timely innovations and future expansions.

---

## Tokenomics – Keeping It Fair

### Block Rewards Schedule

| Block Range     | Reward Per Block (DEV)                            |
| --------------- | ------------------------------------------------- |
| 0–99,999        | 500,000 (first 1k blocks random rewards up to 1M) |
| 100,000–144,999 | 250,000                                           |
| 145,000–199,999 | 125,000                                           |
| 200,000–299,999 | 62,500                                            |
| 300,000–399,999 | 31,250                                            |
| 400,000–499,999 | 15,625                                            |
| 500,000+        | 10,000                                            |

### Predictable, Sustainable, Inflation Model
DogecoinEV keeps **the proven inflationary model of Dogecoin**, ensuring **continuous mining rewards and low fees.** This means **no artificial supply caps—just a steady flow of coins to keep the network moving.**

---

## Technical Specs & Upgrades

### What Makes DogecoinEV Unique?
- **10MB Blocks** – Making room for **more transactions, more data, and more future possibilities.**
- **Merge Mining Activated at Block 30,000** – Because security matters.
- **Optimized for Fast Transactions** – Nobody likes waiting. **One-minute blocks keep things moving.**
- **Custom GUI** – A slick, user-friendly experience designed for everyone, from crypto OGs to total normies.
- **Prefix D** – Addresses start with `D`, paying homage to the original Dogecoin vibe.
- **BIP Activation at Block 1k** – Future-proofing the chain for expansions and improvements.

---

## Under the Hood: ChainParams

Below is a snippet from our `chainparams.cpp` illustrating how our network parameters are set:

```cpp
// Simplified excerpt from chainparams.cpp:

class CMainParams : public CChainParams {
public:
    CMainParams() {
        strNetworkID = "main";
        // BIP is activated at block 1000
        consensus.BIP65Height = 1000;
        consensus.BIP66Height = 1000;
        // Blocks up to 99,999 have 500k rewards, next block ranges halve accordingly
        consensus.nSubsidyHalvingInterval = 100000;
        // Scrypt PoW with 1-minute block times
        consensus.nPowTargetTimespan = 60;
        consensus.nPowTargetSpacing = 60;
        // Chain ID 63
        consensus.nAuxpowChainId = 0x63;
        // PubKey address prefix is 30 (which is 'D')
        base58Prefixes[PUBKEY_ADDRESS] = std::vector<unsigned char>(1,30);
        // Additional chain parameters...
    }
};
```

For a full view, check out our [GitHub repo](https://github.com/DogecoinEV-Foundation/DogecoinEV) where you can see the entire file.

---

## Open-Source & Community-Driven

DogecoinEV is powered by **the people.** This isn’t some centralized, VC-backed, “web3 buzzword” project. **This is a true grassroots movement, just like Dogecoin was in the early days.**

### Contributing to DEV
- **Developers** can submit proposals, pull requests, and fixes via [GitHub](https://github.com/DogecoinEV-Foundation/DogecoinEV).
- **Miners** can help secure the network while earning extra rewards.
- **DEVS** can just use DEV like it was meant to be used—**for fun, for tipping, for sending coins in seconds.**

---

## The Fren-to-Fren Future of DogecoinEV

We believe in **keeping crypto simple, fun, and accessible.** DogecoinEV isn’t about complex DeFi protocols or over-engineered tokenomics. It’s about **bringing back the magic of early crypto—where people sent coins just because they could, and everyone felt like part of something bigger.**

### Use Cases
- **Digital Payments:** Cheap, fast, and easy—just like sending a text.
- **Merge Mining:** Strengthening Dogecoin, Litecoin, and DogecoinEV at the same time.
- **On-Chain Fun:** NFTs, meme games, tipping your favorite creator—**DEV is built for real-world fun.**

---

## Join the DEVS

Be part of something **that actually matters.** DogecoinEV isn’t just a blockchain—it’s a movement.

- **BitcoinTalk:** [DogecoinEV Forum](https://bitcointalk.org/index.php?topic=5529709.0)
- **Website:** [dogecoinev.com](https://dogecoinev.com/)
- **𝕏 (formerly Twitter):** [@DogeElonVision](https://x.com/DogeElonVision)
- **Telegram:** [Doge Elon Vision Community](https://t.me/DogeElonVision)
- **GitHub:** [DogecoinEV-Foundation](https://github.com/DogecoinEV-Foundation/DogecoinEV)

---

## Quick Start

1. **Clone the Repo**: `git clone https://github.com/DogecoinEV-Foundation/DogecoinEV.git`
2. **Build/Install**:
   - Refer to the documentation in the `/doc` folder for build instructions.
3. **Run a Node**:
   - Start up your DogecoinEV node to help secure the network.
4. **Use the Core Wallet**:
   - Easily send & receive DEV, just like you would with Dogecoin.

---

## License
This project is open-source under the [MIT License](LICENSE). Feel free to fork, modify, and distribute as you please.

---

## Final Note

🚀 **DEV: More Transactions. More Fun. More DEV Energy—All Aligned with Elon’s Vision.** 🚀

Take part in the revolution today—where memes meet real utility. DogecoinEV is bridging the gap between unstoppable fun and unstoppable tech. Now it’s your turn to add to the hype. Happy mining and happy sending!

