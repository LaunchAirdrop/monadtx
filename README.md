[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=Welcome+To+Launch+Airdrop)](https://git.io/typing-svg)

# Daily Swap Monad (Rubic, Hedgemony, Taya.fi, Bubble.fi) 
A daily all in one automation bot for interacting with the Monad Ecosystem.

![image](https://github.com/user-attachments/assets/291fc5db-0127-4718-a99c-17725baf2648)


## Feature bot
- Automated wallet login and authentication
- Auto approve (you must approve manually on dex)
- Execute transaction for MON, WMON, and other token
- Bot has random tokens and random times so the system doesn't detect that you are using a bot

### * Don't forget to claim faucet and approve manually (just one time) on: 
- https://testnet.rubic.exchange
- https://app.taya.fi/swap
- https://app.bubblefi.xyz/
- https://app.sherpa.trade/lander

## Installation

Clone the repository
```bash
git clone https://github.com/LaunchAirdrop/monadtx.git
cd monadtx
```

Install packages
```bash
npm install
```

Edit and input Private Key, Bearer, and Cookie:
```bash
nano .env
```

Run the script
```bash
node index.js
```

### * If this bot doesn't work, you can swap manually first.

# How to get Cookie?
1. Go to dex Monad Ecosystem (Rubic and Bubblefi)
2. Login your wallet
3. Approve manually (just one time)
4. Click F12 on your keyboard
5. Click Network
6. Search status_info
7. Scroll and you can see your Cookie
   
![Cookie](https://github.com/user-attachments/assets/b7116c5a-cc03-4cdd-8b92-3debcac03e14)

# How to get Bearer?
1. Go to dex Monad Ecosystem ( Hedgemony )
2. Login your wallet
3. Click F12 on your keyboard
4. Click Application
5. Click Local Storage
6. On Key u can see hedgemony_auth and Value is your Bearer
7. Copy all bearer and paste on .env
   
![Bearer](https://github.com/user-attachments/assets/101c74d8-8807-47aa-8bf0-8904e6819cd6)


# The bot will:
1. Login wallet
2. Display information
3. Process transactions
4. Monitor and display user stats

## Troubleshooting

- Ensure your private keys are in Base58 format
- Verify your wallets
- Check approving and swapping
- Monitor console for error messages

## License

MIT License - See LICENSE file for details

## Disclaimer

This bot is for educational purposes only. Use at your own risk. The maintainers are not responsible for any lost funds or account issues.





