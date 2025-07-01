# BlockElect: Decentralized Election Voting DApp

**BlockElect** is a fully decentralized election voting platform built using **Solidity**, **Next.js**, and **Hardhat**. It leverages blockchain technology to ensure secure, transparent, and tamper-proof elections. This DApp allows users to connect their wallets, vote for candidates, and verify results in real-time.

---

## 🔧 Tech Stack

- **Frontend**: React.js (Next.js)
- **Smart Contracts**: Solidity (Hardhat)
- **Wallet Connection**: Web3Modal
- **IPFS Storage**: Pinata
- **Backend Form Handling**: Formspree
- **Hosting Provider**: DigitalOcean (or your preferred cloud)

---

## 🚀 Features

- ✅ Voter authentication via wallet connection
- ✅ Candidate registration and listing
- ✅ Voting mechanism with one vote per address
- ✅ Real-time result updates
- ✅ IPFS for storing metadata and images securely
- ✅ Contact form with Formspree integration

---

## 🛠️ Setup & Installation

### 1. Install VS Code
[https://code.visualstudio.com/download](https://code.visualstudio.com/download)

### 2. Install Node.js and npm
[https://nodejs.org/en/download](https://nodejs.org/en/download)

Recommended versions:
- Node.js: `v18.12.2` or later
- npm: `v10.5.0`

---


#### PInata IPFS

```https://www.pinata.cloud/
 GET: API_KEY
 GET:  SECRECT_KEY
```

## PInata IPFS IMAGE UPLOAD

```https://www.pinata.cloud/
 headers: {
            pinata_api_key: `YOUR_API_KEY`,
            pinata_secret_api_key: `YOUR_SECRECT_KEY`,
            "Content-Type": "multipart/form-data",
          },
```

## PInata IPFS JSON DATA UPLOAD

```https://www.pinata.cloud/
 headers: {
            pinata_api_key: `YOUR_API_KEY`,
            pinata_secret_api_key: `YOUR_SECRECT_KEY`,
             "Content-Type": "application/json",
          },
```

#### NodeJs & NPM Version

```https://nodejs.org/en/download
  NodeJs: v21.6.2 / latest version
  NPM: 10.5.0
```

#### Test Faucets

Alchemy will provide you with some free test faucets which you can transfer to your wallet address for deploying the contract

```https://faucet.polygon.technology/
  Get: Free Test Faucets
```

#### RemixID

We are using RemixID for deploying the contract and generation of the ABI in the project, but you can use any other tools like Hardhat, etc.

```https://remix-project.org
  OPEN: RemixID
```
#### Formspree

```https://formspree.io/
  CREATE ACCOUNT: https://formspree.io/
  const [state, handleSubmit] = useForm("YOUR_KEY");
```
#### PACKAGE.JSON

```https://www.theblockchaincoders.com/SourceCode
  {
  "name": "voting-organization",
  "version": "0.1.0",
  "private": true,
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint"
  },
  "dependencies": {
    "axios": "^0.27.2",
    "ether": "^0.0.9",
    "next": "12.2.5",
    "react": "18.2.0",
    "react-dom": "18.2.0",
    "react-dropzone": "^14.2.2",
    "react-icons": "^4.4.0",
    "web3modal": "^1.9.9",
    "react-hot-toast": "^2.4.1",
    "@formspree/react": "^2.5.1"
  },
  "devDependencies": {
    "@nomicfoundation/hardhat-toolbox": "^2.0.0",
    "hardhat": "^2.11.2"
  }
}

```
>>>>>>>(Initial commit of my DApp)
