# 🌾 Crop-Defi  
### **Decentralized Crop Insurance using Smart Contracts**

**Live Demo:** https://defi-in-crop-insurance.vercel.app/  

Crop-Defi is a decentralized parametric crop-insurance platform built using **Solidity**, **Next.js**, **Thirdweb**, and **Hardhat**.  
The system automates rainfall-triggered payouts for farmers using oracle-fed weather data.

---

## 🚀 Features

### 👨‍🌾 For Farmers
- Buy crop insurance policies
- Automatic payouts when rainfall drops below threshold
- Track active and past policies

### 🏦 For Insurers
- Provide liquidity to the insurance pool
- View dashboard with total policies, profits, reserves

### 🌧 For Oracles
- Submit rainfall data
- Trigger automated smart-contract-based payouts

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|------------|
| **Smart Contracts** | Solidity, Hardhat |
| **Frontend** | Next.js 15, TypeScript, TailwindCSS |
| **Web3 Toolkit** | Thirdweb SDK |
| **Deployment** | Vercel |
| **Wallets** | MetaMask |

---

## 📁 Project Structure

```

crop-defi/
│
├── frontend/            # Full Next.js frontend (UI + logic)
│   ├── src/
│   ├── public/
│   └── ...
│
├── smart-contract/      # Solidity contracts + Hardhat scripts
│   ├── contracts/
│   ├── scripts/
│   └── hardhat.config.js
│
└── README.md

````

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/IIITLucknowDigiPayments/crop-defi.git
cd crop-defi
````

### 2️⃣ Install Frontend Dependencies

```bash
cd frontend
yarn install
```

### 3️⃣ Install Smart Contract Dependencies

```bash
cd ../smart-contract
yarn install
```

---

## 🧪 Running the Project Locally

### ▶️ Start Frontend

```bash
cd frontend
yarn dev
```

### ▶️ Deploy Smart Contracts (Optional)

```bash
npx thirdweb deploy -k <YOUR_PRIVATE_KEY>
```

---

## 🌍 Deployment

The project is deployed on **Vercel**.

🔗 **Live URL:** [https://defi-in-crop-insurance.vercel.app/](https://defi-in-crop-insurance.vercel.app/)

---

## 🔑 Environment Variables

### Inside `frontend/.env.local`

```
NEXT_PUBLIC_TEMPLATE_CLIENT_ID = your_thirdweb_client_id
NEXT_PUBLIC_CONTRACT_ADDRESS=your_thirdweb_bundle_id
```

---

## 👥 Contributors

| Roll No.       | Name              |
| -------------- | ----------------- |
| **LCB2022019** | Shagun Singh      |
| **LCB2022028** | Vaishnavi Singh   |
| **MDB24017**   | Shuvra Mishra     |
| **MDB24033**   | Priyam Tahabilder |
| **MDB24022**   | Palak Tayal       |
| **MDB24032**   | Shubham Kumar     |
| **MDB24024**   | Suryansh Singh    |
| **MDB24031**   | Dev Joshi         |

---

## 📜 License

MIT License — free to use, modify, and distribute.

---

## ⭐ Acknowledgements

* Thirdweb
* Hardhat
* Chainlink (Oracle inspiration)
