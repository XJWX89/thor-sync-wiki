# Common
## Why there are two Sync in my computer? 
It's two independent projects, therefore, once the wallets are importing to the new sync. You can remove the application from your computer.

## What's the different between new Sync and old Sync ?
After releasing the old version of sync, we realized that it hangs back numerous users because you need to wait for synchronize the blockchain data every time. This waiting greatly reduces the user's experience and loses patience. Moreover, users also need to know certain knowledge of the blockchain before using Sync. This brings a certain threshold and inconvenient to users. In order to make more users understand and experience blockchain easily, this gives us an idea of the new Sync.

The New Sync is providing a seamless experience for end-users and developers. it makes developers and users focus on the content itself, rather than understanding how blockchain works. For example, users no longer need to synchronize block data, just open and use it; simplify the transaction process... and more.

## I already installed the old sync and generated wallets , How can I import the wallets to new Sync ?
1. On old Sync and follow the step  [Export Wallet](https://github.com/vechain/thor-sync/wiki/Account#export-keystore-or-private-key) 
2. Open the file which is generated by Old Sync 
3. Copy the keystore/private key
4. Open New Sync and follow the step [Import Wallet](https://github.com/vechain/thor-sync.electron/wiki/Wallet#import-wallet) 

## Where is old version keystore stored?
- MacOS :` ~/Library/Application\ Support/org.vechain.ua/keystore/`
- Windows: `%APPDATA%\org.vechain.ua/keystore/ `

## Does new sync has a folder store the keystore file  ?
No, only if user backup(export)  the wallet will generate the keystore file. 

Please check [Export wallet](https://github.com/vechain/thor-sync.electron/wiki/Wallet#export-keystore)

## How to get test token ?
You can visit [Faucet](https://faucet.vecha.in/)


# Technical 
## Certificate of Identification VS Certificate of Agreement
The certificate is a message signing based mechanism which can easily request a user's identification(address) or a user agree to DApp term of use or service.

The purpose of the certificate of identification is a way that allows Dapps to send you a random challenge to prove that you are the owner of the wallet. **It proves that you are the owner of the wallet.**

On other hands, the certificate of agreement is a certificate that you agree to DApp's term of use or service. The agreement come in many forms before you agree to the content, please always review the content which provided by DApp. Once you signed the agreement. **it  proves that you are the wallet owner and agree to the DApp's term of use or service.**


## How to connect node ?
1. [Run thor](https://github.com/vechain/thor#running-thor)
2. Open Sync
3. Follow the step to [add custom node](https://github.com/vechain/thor-sync.electron/wiki/Browse-DApp&Web#add--custom-node)

## How to open developer tools?
1. Right click the mouse 
2. Click "**Inspect Element**"