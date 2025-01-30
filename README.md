# LayerEdge Automation Bot

An automation tool designed to help users manage their LayerEdge light nodes efficiently with a convenient terminal-based dashboard interface.

## Features

- Secure Private Key Management
- Auto Node Activation & Ping
- Points Tracking System
- Multi-wallet Support
- Interactive Terminal Dashboard
- Colored Status Indicators
- Pagination for Multiple Accounts
- Auto Referral Feature

## Prerequisites

Before running the bot, make sure you have:

- Node.js (v16 or higher)
- npm (Node Package Manager)
- A LayerEdge account
- Wallet private keys for activation

## Registration

1. Visit [LayerEdge Dashboard](https://dashboard.layeredge.io)
2. Enter the referral code: `7FYJLWy2`
3. Connect your wallet and complete the registration
4. Start earning points by running a light node!

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Rambeboy/LayerEdge-BOT.git
```

2. Navigate to the project directory:

```bash
cd LayerEdge-BOT
```

3. Install dependencies:

```bash
npm install && npm run setup
```

4. Configure your wallets:
- Edit `data.txt` file in the root directory
- Add your wallet private keys (one per line)`

5. Configure bot config to run autoref
```bash
nano config/config.js
```

6. Run bot Autoref
```bash
npm run autoref
```

7. Start the bot
```bash
npm run start
```

## Controls

- ↑/↓: Navigate between wallets
- ←/→: Change pages
- Ctrl+C: Exit program

## Features Explained

### Secure Key Management

- Reads private keys from data.txt
- Automatically derives wallet addresses
- Secure signing for node activation

### Node Activation & Ping

- Automatic node status checking
- Signature-based node activation
- Continuous ping to maintain node status
- Configurable ping interval

### Status Monitoring

- Real-time status updates
- Points tracking
- Detailed error reporting
- Multiple status indicators:
- 🔵 Starting: Initial setup
- 🟡 Checking Status: Verifying node status
- 🟣 Activating: Node activation in progress
- 🟢 Active: Node running successfully
- 🔴 Error: Error encountered
- 🟢 Activated: Node activation successful

### Dashboard Interface

- Clean and intuitive terminal interface
- Real-time updates
- Color-coded status indicators
- Pagination for multiple wallets
- Error message display

## Security Notice

**Important**: Your private keys are sensitive information. Never share them with anyone and ensure `data.txt` is properly secured and not shared publicly.

## Contributing

Contributions are welcome! Please feel free to submit pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

This bot is provided as-is, without any warranties. Users are responsible for their own actions and should use this tool responsibly. Never share your private keys and always verify the source code before running any automated tools.
