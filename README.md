# ERC20 Intern Reward Token (IRT)

This project contains an ERC20-based Intern Reward Token smart contract developed using Solidity and deployed on the SecureChain (SCAI) Mainnet using Remix IDE and MetaMask.

The project demonstrates how to create, compile, deploy, and add a custom ERC20 token to MetaMask as a beginner.

---

# Project Objective

The main objective of this project is to:

- Learn smart contract development
- Understand ERC20 token basics
- Deploy a token on blockchain
- Connect MetaMask wallet
- Use Remix IDE for deployment
- Add custom token into MetaMask

---

# Technologies Used

| Technology | Purpose |
|------------|---------|
| Solidity | Smart contract programming |
| Remix IDE | Writing and deploying contracts |
| MetaMask | Blockchain wallet |
| SecureChain Mainnet | Blockchain network |
| GitHub | Project hosting |

---

# Token Details

| Property | Value |
|----------|-------|
| Token Name | Intern Reward Token |
| Token Symbol | IRT |
| Decimals | 18 |
| Total Supply | 1000 Tokens |

---

# Step-by-Step Process

---

# Step 1 — Install MetaMask

MetaMask browser extension was installed from:

https://metamask.io

After installation:

- A new wallet was created
- Secret recovery phrase was saved securely

---

# Step 2 — Add SecureChain Mainnet

SecureChain Mainnet was added using:

https://chainlist.org/chain/34

Steps followed:

1. Open Chainlist
2. Connect MetaMask wallet
3. Search for SecureChain Mainnet
4. Click "Add to MetaMask"
5. Approve network addition

---

# Step 3 — Get Free SCAI Coins

Free SCAI coins were collected from faucet:

https://faucet.securechain.ai

Steps followed:

1. Copy MetaMask wallet address
2. Paste wallet address in faucet
3. Click Send Faucet
4. Receive free SCAI tokens for gas fees

---

# Step 4 — Open Remix IDE

Remix IDE was opened using:

https://remix.ethereum.org

Remix IDE is an online platform used for:
- Writing Solidity code
- Compiling contracts
- Deploying smart contracts

---

# Step 5 — Create Solidity File

Inside Remix IDE:

1. Click File Explorer
2. Click Create New File
3. Create file named:

```solidity
InternRewardToken.sol
```

# Step 6 — Write Smart Contract Code

After creating the Solidity file, the ERC20 smart contract code was added into:

```solidity
InternRewardToken.sol
```
The smart contract contains:

- Token Name
- Token Symbol
- Total Supply
- Transfer functionality
- Balance mapping

This file was used for compiling and deploying the ERC20 token on SecureChain Mainnet.

# Step 7 — Compile the Smart Contract

Steps followed:

1. Open Solidity Compiler
2. Select compiler version `0.8.20`
3. Click Compile InternRewardToken.sol

After successful compilation:
- Green checkmark appeared
- No errors were found

---

# Step 8 — Connect MetaMask to Remix

Steps followed:

1. Open Deploy & Run Transactions
2. Select Environment:
   - Injected Provider - MetaMask
3. MetaMask popup appeared
4. Click Connect

Now Remix IDE connected to MetaMask wallet.

---

# Step 9 — Deploy the Smart Contract

Steps followed:

1. Click Deploy button
2. MetaMask popup opened
3. Gas fee details appeared
4. Click Confirm

After few seconds:
- Smart contract deployed successfully
- Transaction confirmed on blockchain

---

# Step 10 — Verify Deployment

After deployment:

- Contract appeared under Deployed Contracts
- Contract address was generated
- Functions became visible

Functions checked:
- name()
- symbol()
- totalSupply()

Outputs:
- Intern Reward Token
- IRT
- 1000 Tokens
<img width="1437" height="769" alt="Screenshot 2026-05-21 125404" src="https://github.com/user-attachments/assets/3ad4f064-ce37-454a-b8b2-448658ac32ce" />

---

# Step 11 — Add Token to MetaMask

Steps followed:

1. Open MetaMask
2. Click Import Tokens
3. Paste deployed contract address
4. Token details auto-filled
5. Click Import
<img width="456" height="861" alt="Screenshot 2026-05-21 125227" src="https://github.com/user-attachments/assets/359eff28-3b7d-442f-b42d-6745caea0fff" />

After importing:
- IRT token became visible in MetaMask wallet
<img width="457" height="631" alt="Screenshot 2026-05-21 125310" src="https://github.com/user-attachments/assets/c3ff1223-3c4d-46f3-b28e-862b6462df54" />
---

# How to Run This Project

1. Install MetaMask
2. Add SecureChain Mainnet
3. Get faucet tokens
4. Open Remix IDE
5. Create Solidity file
6. Paste contract code
7. Compile contract
8. Connect MetaMask
9. Deploy smart contract
10. Import token into MetaMask
