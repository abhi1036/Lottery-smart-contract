# Ethereum Lottery Smart Contract 🎰

This is a simple **Lottery Smart Contract** built using Solidity. Participants can enter the lottery by sending **2 ETH**, and a manager can pick a random winner.

## 🚀 Features
- **Minimum 3 participants required** before selecting a winner
- Uses `keccak256` for randomization (not truly random, but works for testing)
- Only the **manager** can check the contract balance and select a winner

## 📌 How It Works
1. Deploy the contract on **Remix IDE** or a **Testnet** (Goerli, Sepolia)
2. Participants enter by sending **2 ETH** (`receive()` function)
3. The **manager selects a winner**, and the contract transfers the prize money

## 📜 Smart Contract Code
Check the [`Lottery.sol`](./Lottery.sol) file for the full code.

## 📺 Demo Video
[Watch the demo on LinkedIn](#) (Upload your video first, then add the link here)

## 💡 Improvements
- Use **Chainlink VRF** for secure randomness
- Add a **withdrawal function** for refunds

## 🛠 Tech Stack
- Solidity
- Ethereum
- Remix IDE
- MetaMask
