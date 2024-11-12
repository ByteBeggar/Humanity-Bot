# Humanity Testnet Auto Claimer

An automated bot for claiming THP tokens and rewards on the Humanity Protocol testnet.

## Features
- Multi-Account Proxy
- Automatically claims THP from faucet
- Auto claims rewards
- Performs bridge operations when conditions are met
- Supports multiple wallets
- Beautiful colored console output
- Automatic retry mechanism
- Error handling and recovery
- Accurate countdown timers

## Requirements

- Node.js v16 or higher
- npm or yarn package manager

## Installation

1. Clone this repository:

```bash
git clone https://github.com/ByteBeggar/Humanity-Bot.git
cd Humanity-Bot
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Set up your private keys:
   Edit `data.txt` one private key package per line excluding 0x 

```
private No 0x

```

4. Edit `proxy.txt` one per line

```
socks5://host:proxy
socks5://host:proxy
socks5://host:proxy

```


## Usage

1. First, register on Humanity Protocol:
   [Register Here](https://testnet.humanity.org/login?ref=sanyan)

2. Input code: sanyan

3. Run the bot:

```bash
node main.js
```

## Features Explanation

- **Automatic THP Claiming**: Claims THP from faucet every 8 hours
- **Reward Claiming**: Automatically attempts to claim rewards when available
- **Bridge Operations**: Performs bridge transactions when balance conditions are met
- **Multi-wallet Support**: Processes multiple wallets sequentially
- **Smart Retry System**: Automatically retries failed operations
- **Colorful Console Output**: Easy-to-read, color-coded console messages

## Default Timings

- Wait between wallets: 3 seconds
- Wait between claim rounds: 8 hours
- Retry delay: 5 seconds
- Claim attempts: 3 times before giving up

## Important Constants

```javascript
MIN_BALANCE_FOR_REWARD: 0.001 THP
MIN_BALANCE_FOR_BRIDGE: 1.1 THP
BRIDGE_AMOUNT: 1 ETH
```
## 🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀


