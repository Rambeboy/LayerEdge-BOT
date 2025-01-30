# LAYER EDGE BOT

An automation tool designed to help users manage their LayerEdge light nodes efficiently with a convenient terminal-based dashboard interface.

## BOT FEATURE

- Secure Private Key Management
- Auto Node Activation & Ping
- Points Tracking System
- Multi-wallet Support
- Interactive Terminal Dashboard
- Colored Status Indicators
- Pagination for Multiple Accounts
- Auto Referral Feature

## PREREQUISITE

Before running the bot, make sure you have:

- Node.js (v16 or higher)
- npm (Node Package Manager)
- A LayerEdge account
- Wallet private keys for activation

## REGISTRATION

1. Visit [LayerEdge Dashboard](https://dashboard.layeredge.io)
2. Connect your wallet and complete the registration
3. Start earning points by running a light node!

## INSTALLATION

1. Clone the repository:

```bash
git clone https://github.com/Rambeboy/LayerEdge-BOT.git && cd LayerEdge-BOT
```
2. Install dependencies:

```bash
npm install && npm run setup
```

3. Configure your wallets:
- Edit `data.txt` file in the root directory
- Add your wallet private keys (one per line)`

4. Configure bot config to run autoref
```bash
nano config/config.js
```

5. Run bot Autoref
```bash
npm run autoref
```

6. Start the bot
```bash
npm run start
```

## CONTROLS

- ↑/↓: Navigate between wallets
- ←/→: Change pages
- Ctrl+C: Exit program

## FEATURES EXPLAINED

### SECURE KEY MANAGEMENT

- Reads private keys from data.txt
- Automatically derives wallet addresses
- Secure signing for node activation

### NODE ACTIVATION & PING

- Automatic node status checking
- Signature-based node activation
- Continuous ping to maintain node status
- Configurable ping interval

### STATUS MONITORING

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

### DASHBOARD INTERFACE

- Clean and intuitive terminal interface
- Real-time updates
- Color-coded status indicators
- Pagination for multiple wallets
- Error message display

## SECURITY NOTICE

**Important**: Your private keys are sensitive information. Never share them with anyone and ensure `data.txt` is properly secured and not shared publicly.

## LICENSE

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## DISCLAIMER

This bot is provided as-is, without any warranties. Users are responsible for their own actions and should use this tool responsibly. Never share your private keys and always verify the source code before running any automated tools.
