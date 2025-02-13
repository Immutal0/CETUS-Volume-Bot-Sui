# SUI Volume Bot (CETUS-DEX)

The **SUI Volume Bot** is designed to perform continuous buy and sell transactions on the CETUS DEX platform, boosting trading volume and increasing maker liquidity. The bot operates automatically, optimizing transactions and gas fees to the minimum.

> **Note**: The original project is written in TypeScript. The version in this repository is a compiled demo. For the full version, feel free to contact me on [Telegram](https://t.me/Immutal0) or [Twitter](https://twitter.com/Immutal0_).

## 🌟 Features

- ⚙️ **Automated SUI Distribution**: Automatically distributes SUI tokens to new wallets.
- 🔄 **Endless Buy and Sell Swaps**: Executes continuous buy and sell transactions on the CETUS DEX platform.
- 🛠️ **Customizable Parameters**: Provides flexibility for adjusting buy amounts, intervals, and distribution settings.

## 📋 Environment Variables

To run the bot, you'll need to set up a few environment variables. Rename the `.env.copy` file to `.env` and update the variables accordingly.

```env
PRIVATE_KEY=your_private_key

NETWORK=mainnet

RPC_ENDPOINT=https://rpc.ankr.com/sui/<RPC_API_KEY>
RPC_WEBSOCKET_ENDPOINT=wss://rpc.ankr.com/sui/ws/<RPC_API_KEY>

DISTRIBUTE_INTERVAL_MAX=30  # seconds
DISTRIBUTE_INTERVAL_MIN=20  # seconds

BUY_INTERVAL_MAX=10    # seconds
BUY_INTERVAL_MIN=5     # seconds

SWAP_AMOUNT_MAX=0.5   # SUI 
SWAP_AMOUNT_MIN=0.1   # SUI 

POOL_ID=0x1de5cc16141c21923bfca33db9bb6c604de5760e4498e75ecdfcf80d62fb5818
```

## 🚀 Usage

### 1. Clone the repository

```bash
git clone https://github.com/Immutal0/CETUS-Volume-Bot-Sui.git
cd CETUS-Volume-Bot-Sui
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure the environment variables

Rename the `.env.copy` file to `.env` and configure the RPC endpoint, WebSocket, the main keypair's secret key, and other relevant settings.

### 4. Run the bot

```bash
npm start
```

### 5. Gather funds from distributed wallets

```bash
npm run gather
```

## 👤 Author

- **Twitter**: [@Immutal0](https://x.com/Immutal0_)  
- **Telegram**: [@Immutal0](https://t.me/Immutal0)  

Feel free to reach out on these platforms for support or to inquire about other projects.
