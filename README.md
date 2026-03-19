# 🧠 To-Do List on Blockchain

### A Decentralized Task Manager built with Soroban (Stellar)

---

## 📌 Project Description

Traditional to-do list applications store data on centralized servers, making them vulnerable to data loss, manipulation, and lack of transparency.

This project reimagines task management using blockchain technology by building a **decentralized To-Do List** on the Stellar network using **Soroban smart contracts**.

By leveraging blockchain, tasks become **tamper-proof, transparent, and permanently stored**, giving users full control over their data without relying on any centralized authority.

---

## ⚙️ What it does

This smart contract enables users to manage their tasks directly on-chain. Users can:

* ➕ Add new tasks
* 📋 Retrieve all existing tasks
* ✅ Mark tasks as completed

All operations are executed through the Soroban smart contract, ensuring that the data is **secure, immutable, and verifiable**.

---

## ✨ Features

### 🔐 Decentralized Storage

All tasks are stored on the blockchain, eliminating dependency on centralized databases.

### 🧾 Task Management

Users can easily create and manage their to-do items.

### ✅ Completion Tracking

Tasks can be marked as completed, enabling progress tracking.

### ⚡ Fast & Efficient

Built on Soroban, ensuring low-cost and high-performance execution.

### 🧩 Developer-Friendly

Simple architecture makes it easy to extend into more advanced dApps.

---

## 🔗 Deployed Smart Contract Link

**To-Do List on Blockchain**

---

## 🛠️ Tech Stack

* **Rust** – Smart contract development
* **Soroban SDK** – Blockchain interaction layer
* **Stellar Network** – Decentralized infrastructure

---

## 🚀 Getting Started

### 1️⃣ Install Soroban CLI

```bash
cargo install soroban-cli
```

### 2️⃣ Build the Contract

```bash
soroban contract build
```

### 3️⃣ Deploy the Contract

```bash
soroban contract deploy \
  --wasm target/wasm32-unknown-unknown/release/todo_contract.wasm \
  --source YOUR_ACCOUNT
```

---

## 🧪 Interacting with the Contract

### ➕ Add a Task

```bash
soroban contract invoke \
  --id CONTRACT_ID \
  --fn add_task \
  --arg task="Learn Blockchain"
```

### 📋 Fetch All Tasks

```bash
soroban contract invoke \
  --id CONTRACT_ID \
  --fn get_tasks
```

### ✅ Mark Task as Completed

```bash
soroban contract invoke \
  --id CONTRACT_ID \
  --fn complete_task \
  --arg index=0
```

---

## 🧱 Architecture Overview

```
User → Soroban Smart Contract → On-Chain Storage
```

* User interacts via CLI or frontend
* Smart contract processes logic
* Data is stored permanently on blockchain

---

## 📈 Future Improvements

* 👤 Wallet-based user authentication (multi-user support)
* 🗂️ Task categories & priority levels
* ⏰ Deadlines and reminders
* 🌐 Frontend integration (React / Next.js)
* 📊 Analytics for productivity tracking

---

## 💡 Why this Project Matters

This project demonstrates how even simple applications can benefit from decentralization:

* No single point of failure
* Transparent data handling
* User-owned data

It serves as a **foundation for building more complex decentralized applications (dApps)**.

---

Contract Address: CDGLWEIH4HGSLLV62GU3AFA4FW6Q6AL45KFC77P3WAEKEA2N2TEUUXHDF


---

<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/3fc0babe-fa6e-4149-9f3e-a25866be2022" />


MIT License
