# WalletPersona 🔍💼

*AI-Powered Web3 Identity Engine* 
*"Your Wallet. Your Story."*

# 🚀 Overview

**WalletPersona** is a Web3-powered AI tool that analyzes an Ethereum wallet’s on-chain activity to generate a unique user **persona**. It transforms raw blockchain data into readable insights — classifying the wallet as an investor, NFT collector, DAO member, newbie, or even a high-risk actor.

Built for a Web3 hackathon, this project demonstrates how identity and personalization can be inferred from wallet behavior — without any KYC or off-chain data.

# 🧠 Key Features

- 🔗 **Ethereum Wallet Input** – Paste any Ethereum address or connect MetaMask.
- 📊 **Behavioral Analytics** – Tracks transactions, NFTs, tokens, contract interactions.
- 🧬 **Persona Classification** – Identifies user types using AI-inspired logic.
- 🧾 **AI-Generated Bio** – Textual summary of the wallet's behavioral profile.
- 📈 **Visual Insights** – Interactive charts of wallet activity.
- 🧪 **Fully Open Source** – No subscriptions, no paid APIs. 100% accessible.


## 🌐 Live Demo

Coming Soon...

# 🛠️ Tech Stack

- **Frontend**: React.js
- **Blockchain Access**: ethers.js
- **Styling**: Tailwind CSS
- **Charts**: Recharts / Chart.js
- **Hosting**: Netlify or localhost


# 🔍 How It Works

1. **Input Wallet**: User pastes an Ethereum wallet address or connects MetaMask.
2. **Fetch Data**: ethers.js fetches:
   - Transactions
   - Token balances
   - NFT transfers
   - Contract interactions
3. **Classify Persona**:
   - 🎨 *NFT Collector*: High NFT interaction
   - 💰 *Investor*: Token swaps, DeFi activity
   - 🧑‍🤝‍🧑 *DAO Member*: DAO-related contracts
   - 🆕 *Newbie*: Low activity
   - ⚠️ *Risky*: Suspicious or volatile tokens
4. **Generate Profile**:
   - AI-written bio
   - Visual graphs
   - Behavior breakdown

# 🧪 Example Output

Wallet: 0x1234...abcd
Persona: NFT Collector
AI Bio: "A vibrant NFT enthusiast, consistently collecting early-mint gaming and art assets. Engaged with emerging Web3 social platforms."

# 📦 Installation

bash
git clone https://github.com/yourusername/walletpersona.git
cd walletpersona
npm install
npm start
`

> Make sure you have Node.js and npm installed.



# 🧩 Future Enhancements

* 🔁 Cross-chain wallet support (Polygon, BSC, etc.)
* 🤖 GPT-based dynamic bio generation
* 🛡️ Wallet risk scoring engine
* 🧩 Browser plugin integration
* 🌐 Personalized dApp/NFT suggestions


