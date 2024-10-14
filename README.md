<h2 align=center> Contract Deployer Script For any EVM Chain (Testnet or Mainnet) </h2>

## Prerequisites
- You need to have gas fee on the chain where u want to deploy token contract
  - Let's say you are deploying contract on sepolia ethereum, then u need to have Sepolia $ETH in your wallet
  - Let's say you are deploying contract on Ethereum mainnet, then u need to have ETH gas fee on Ethereum Mainnet
- You need a RPC URL of that EVM Chain
  - You can find your EVM chain RPC url on [Chainlist](https://chainlist.org)
- Need to have terminal which support linux based command
   - You can use either local terminal (Ubuntu)
   - Or you can use Virtual IDE like [codespaces](https://github.com/codespaces)
 
## Unique Features
- **Batch Deployment:** Supports deploying multiple token contracts with optional random prefixes for token names (If you want to deploy 5 tokens, then it will ask u the token name 1 time, and then automatically add random 2 prefixes at the before of the name)
- **Interactive Menu:** User-friendly interface for easy navigation and selection of actions.

## Installations
- You can use either this command
 ```bash
  [ -f "EVM.sh" ] && rm EVM.sh; wget -q https://raw.githubusercontent.com/BidyutRoy2/Contract-Deployer-EVM/refs/heads/main/EVM.sh && chmod +x EVM.sh && ./EVM.sh
```
- Or this command to run this script
```bash
  [ -f "EVM.sh" ] && rm EVM.sh; curl -sSL -o EVM.sh https://raw.githubusercontent.com/BidyutRoy2/Contract-Deployer-EVM/refs/heads/main/EVM.sh && chmod +x EVM.sh && ./EVM.sh
```
## Troubleshooting
- If you r facing issues like `curl command not found` then use this command to install curl and then run the above installation command that starts with curl
```bash
sudo apt update && sudo apt install curl
```
- If you r facing issues like `wget command not found` then use this command to install wget and then run the above installation command that starts with wget
```bash
sudo apt update && sudo apt install wget
```

# ▄︻デ𝙂𝙚𝙩 𝙇𝙖𝙩𝙚𝙨𝙩 𝘼𝙞𝙧𝙙𝙧𝙤𝙥𝙨 & 𝙐𝙥𝙙𝙖𝙩𝙚𝙨═━一

### ▄︻デ𝙅𝙤𝙞𝙣 𝙏𝙚𝙡𝙚𝙜𝙧𝙖𝙢═━一 [🎀  𝐻𝒾𝒹𝒹𝑒𝓃 𝒢𝑒𝓂  🎀](https://t.me/hiddengemnews) 

### ░▒▓█►─═  𝓗𝓲𝒹ᗪ𝓔η Ǥέ𝕄 ═─◄█▓▒░
