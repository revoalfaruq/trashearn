# Trashearn
Trashearn is a decentralized application on PortalDot that enables users to submit and verify environmental actions on-chain, building a scalable Proof-of-Good system for real-world impact.
# 🌱 Trashearn

A Web3 dApp built on PortalDot.

## Features
- Connect Wallet
- Submit Proof
- On-chain data

## How to Run

1. Jalankan node:
./portaldot_dev --dev --alice

2. Buka:
index.html

## Network
ws://127.0.0.1:9944

## Transaction screenshot
![alt text](https://github.com/revoalfaruq/trashearn/blob/main/Folder/UI.jpg?raw=true)
## ⚙️ How Trashearn Works

Trashearn is a simple decentralized application (dApp) built on the PortalDot network that transforms real-world environmental actions into verifiable on-chain records.

### 🔗 1. Wallet Connection

Users connect their wallet using the PortalDot browser extension.
This ensures that every action is linked to a unique on-chain identity without relying on centralized accounts.

---

### 📝 2. Submit Environmental Action

Users input a description of the waste they collect (e.g., “plastic bottles”, “trash cleanup”).
This acts as a basic “proof” of real-world activity.

---

### ⛓ 3. On-Chain Recording

The submitted data is converted into a JSON string and sent to the blockchain using a lightweight transaction:

```
system.remark
```

This transaction:

* stores the data on-chain
* requires gas fees (POT)
* is signed by the user’s wallet

---

### 🔍 4. Transaction Verification

Each submission generates a unique transaction hash (TX Hash).
This allows anyone to verify the action through a blockchain explorer.

---

### 📦 5. Immutable Proof

Once included in a block:

* the data cannot be changed
* it becomes a permanent record of the user’s action
* it contributes to a transparent “Proof-of-Good” system

---

## 🌱 Summary Flow

1. Connect Wallet
2. Enter waste description
3. Submit proof
4. Transaction sent to PortalDot
5. Data stored on-chain
6. TX Hash generated for verification

---

## 💡 Key Idea

Trashearn introduces a **Proof-of-Good mechanism**, where positive real-world actions are:

* recorded on-chain
* publicly verifiable
* potentially rewardable in future iterations

This bridges the gap between **physical environmental impact** and **decentralized blockchain systems**.

