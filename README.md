# DARQade - Web3 Gaming Platform

DARQade is a revolutionary gaming platform that combines AI, blockchain technology, and game development to create unique GameFi experiences. The platform enables game developers to create and monetize games while allowing players to earn rewards through gameplay.

## Features

### For Game Developers
- Create and deploy blockchain-integrated games
- Custom token creation for game economies
- Revenue tracking and analytics
- AI-powered game asset generation
- Flexible pricing plans
- Cross-platform deployment support

### For Players
- Play-to-earn mechanics
- Collection of game-specific meme coins
- AI-powered dynamic gameplay
- Community tournaments
- Cross-game token utility
- Wallet integration with Base network

## Technology Stack

- **Backend**: Flask (Python)
- **Frontend**: HTML, TailwindCSS, JavaScript
- **Blockchain**: Web3.py, Avalanche C-Chain & Arbitrum
- **Database**: Distributed database system with node replication
- **AI Integration**: LangChain, CDP Agentkit
- **Asset Storage**: Cloudinary
- **Authentication**: Custom JWT-based system

## Prerequisites

- Python 3.8+
- Node.js and npm
- Web3 provider (e.g., MetaMask)
- Avalanche C-Chain & Arbitrum Network connection
- Environment variables setup

## Installation

1. Clone the repository:
```bash
git clone https://github.com/DARQ-Lord/Agentathon-DARQade.git
cd darqade
```

2. Install Python dependencies:
```bash
pip install -r requirements.txt
```

3. Set up environment variables:
```bash
cp .env.example .env
```

4. Configure your `.env` file with the following variables:
```bash
INFURA_KEY
PRIVATE_KEY
ORG_SECRET_KEY
ORG_DID
NODE_A_URL
NODE_A_DID
NODE_B_URL
NODE_B_DID
NODE_C_URL
NODE_C_DID
CDP_API_KEY_NAME
CDP_API_KEY_PRIVATE_KEY
OPENAI_API_KEY
CLOUDINARY_CLOUD_NAME
CLOUDINARY_API_KEY
CLOUDINARY_API_SECRET
```

5. Run the application:
```bash
python app.py
```

## Project Structure

```
Flask-Application/
├── app.py              # Main application file
├── utils.py            # Utility functions
├── static/            
│   └── images/*        # Image assets
├── templates/
│   ├── index.html     # Game developer interface
│   └── user_index.html # Player interface
│   └── dashboard.html # Game developer interface
│   └── arcade.html # Player interface
└── requirements.txt    # Python dependencies
```

## Demo
[![Demo Video](https://img.youtube.com/vi/tOo0tRU8eXk/maxresdefault.jpg)](https://www.youtube.com/watch?v=tOo0tRU8eXk)

## Onchain Transactions

### Smart Contracts
#### Avalance
 - https://testnet.avascan.info/blockchain/c/address/0x5bC1AE2064Ae9979652080A7f0Afd64E423F60bC
#### Arbitrum
 - https://sepolia.arbiscan.io/address/0xa9f47865c4742229ccd16e565f89e15e7d1e88ac

### AI Token Prize Distribution
#### Avalance
 - https://testnet.avascan.info/blockchain/c/tx/0x9b272c3db392c092948682873091bd9768b9a4d2449820e702612c4b85a793a9
#### Arbitrum
 - https://sepolia.arbiscan.io/tx/0x9d6b75db9b0770b3d3f687f98ac8e0be0bc048e053a32b958f2397dac62666e7
### AI Game Fee Collection
 - https://testnet.avascan.info/blockchain/c/tx/0x947c4a8f88592c5bc0bdbc5633d6e10fa826c81180031be6b12f0a509c7e3489
 - https://testnet.avascan.info/blockchain/c/tx/0x766bcfb5b9b3130f2a92cb56fc75094695274343eb8c7e8fd2f4bd00b167a303


## Contact

For any inquiries, please reach out through email:  infantsamchris@gmail.com

## Acknowledgments
- Avalanche C-Chain & Arbitrum for blockchain infrastructure
- Nillion for SecretVault Data Storage And the lightweight decentralized AI
- Coinbase Developer Platform for CDP Wallet intergation through Agentkit
- OpenAI & LangChain for setting the base for AI capabilities