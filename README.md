## MANGO TESTNET AUTO BOT

**Register** : [HERE](https://task.testnet.mangonetwork.io/?invite=Hkm9nF)

- [Download Mango Wallet Extension](https://chromewebstore.google.com/detail/mango-wallet/jiiigigdinhhgjflhljdkcelcjfmplnd)
- Backup Phrase
- Claim Faucet on your Wallet extension
- [Register Mango Testnet Here](https://task.testnet.mangonetwork.io/?invite=Znfzo0)
- Complete Bind Social Media Accounts and JOIN NOW
- Go to Event Page
- Complete Task on the Task List ( Swap , Bridge )
- Login Daily
- Done

**LFG**

## PREREQUISITE

- Git
- Node JS (v22)

 ## BOT FEATURE

- Multi Account 
- Support PK
- Proxy Support
- Daily Claim Faucet
- Daily Mango Swap 
- Daily BeingDex Beta DAPP
- Daily Check In
- Daily Bridge 

## SETUP & CONFIGURE BOT

### LINUX

1. Run installation script
   ```
   source <(curl -s https://raw.githubusercontent.com/ryzwan29/mango-testnet/main/quick-installation.sh)
   ```
2. Configure your accounts
   ```
   nano accounts/accounts.js
   ```
3. Configure the bot config
    ```
   nano config/proxy_list.js
    ```
4. Configure your Raw Bridge Data
   ```
   nano config/config.js
   ```
5. To run Auto TX
   ```
   npm run start
   ```

## Get your Raw Bridge Data
1. Bridge your assets from `ETH Sepolia or BNB Testnet > Mango Testnet`
2. Open transaction history in Blockchain Explorer
3. Copy your `Input Data` (e.g. `0x4737ba7a...`)
4. Put your `Input Data` to `Raw Bridge Data` on file `config/config.js`

## UPDATE BOT

To update bot follow this step :
1. Run
   ```
   git pull
   ```
   or
   ```
   git pull --rebase
   ```
   If error run
   ```
   git stash && git pull
   ```
2. Run
   ```
   npm update
   ```
3. Start the bot
4. If any eror happen check `log/app.log`


## IMPORTANT NOTE (READ IT THIS IS NOT DECORATION)
DWYOR & Always use a new wallet when running the bot, I am not responsible for any loss of assets.

## LICENSE

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

**Source : https://github.com/im-hanzou/Mango-Testnet-Auto-Bot**
