# Core Smart Contract Templates 

Welcome to the **Core DAO Smart Contract Starter Templates** repository!  
This repo is designed for beginners deploying their **first smart contracts on Core**.  
Each contract is simple, practical, and helps you understand how smart contracts work in real-world use cases.

---

## What’s Inside?

This repo includes **3 beginner-friendly smart contracts**:

---

### 1. TimeLockWallet.sol

**Purpose:**  
Let users lock ETH inside a contract and withdraw only after a certain time.

**Use Case:**  
Simulates saving goals, token vesting, or delayed withdrawals.

**Features:**
- Deposit ETH with a lock period.
- Withdraw after time has passed.
- Check remaining time before funds unlock.

---

### 2. VotingSystem.sol

**Purpose:**  
A simple decentralized voting system where each address can vote once.

**Use Case:**  
Governance, DAO proposals, or community polling.

**Features:**
- Anyone can create a proposal.
- One address = one vote.
- View all proposals and their vote count.

---

### 3. TokenFaucet.sol

**Purpose:**  
Distribute tokens in small amounts with time-based limits.

**Use Case:**  
Testnet token faucets, community airdrops, or gamified rewards.

**Features:**
- Users can request tokens once every 24 hours.
- Easily connect any ERC20 token.
- Prevents abuse through cooldown mechanism.

