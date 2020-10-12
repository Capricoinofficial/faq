# Capricoin+ Ledger Wallet

## Ledger Nano S is a hardware wallet which stores user's private keys in a secure hardware device

Hardware wallets have major advantages over standard software wallets: **private keys are stored in a secure chip, and cannot be transferred out of the device**. That means your funds are safe even when connected to an infected or malicious computer or a phishing/scam web page.

For these reasons, we highly recommend users to protect their funds by setting up a Ledger Nano S or Nano X.

*This guide should work for all of hardware wallets from Ledger, which support altcoins.*

# Requirements

Before starting the setup process, make sure you have:
- **Ledger Nano S** or **Ledger Nano X** hardware wallet – initialized and [updated to latest firmware](https://support.ledgerwallet.com/hc/en-us/articles/360002731113-Update-Ledger-Nano-S-firmware)
- Ledger Live app [ready to use](https://support.ledger.com/hc/en-us/articles/360006395233)
- Capricoin+ Core wallet installed and fully synced to the Capricoin+ network

*Linux users: Make sure you have added the udev rules to allow device access – see Fix connection issues (under Linux tab) for more info. If you already have a working Ledger wallet, you can skip this.*

# Installation

## Ledger Capricoin+ app
First, we need to install Capricoin+ on your Ledger device (feel free to follow official Ledger's guide though it's the same):

1. open the Manager in Ledger Live
2. connect and unlock your Ledger Nano S
3. if asked, allow the manager on your device by pressing the right button
4. find Capricoin+ app in the catalog
5. click the Install button of the app

Note that if you're forced to uninstall Capricoin+ app from your Ledger (due to lack of space), you'll have to repeat these steps to access your funds. Don't worry, your coins will stay safe even if the app isn't installed in the meantime.

# Capricoin+ Core configuration

If you already have a Capricoin+ wallet on this computer, make sure to back the wallet.dat file up by renaming or moving it elsewhere!

![HD Wallet Setup Screen](https://capricoin.org/images/guide/hd-wallet-screen.jpg) ![waiting for device screen](https://capricoin.org/images/guide/waiting-for-device-screen.jpg) 

1. launch Capricoin+ Core on your computer
2. go to Window → HD Wallet (if it's the first time you're setting up a wallet on this computer or if you don't have any wallet.dat file in your Capricoin+ config folder, then Capricoin+ Core will automatically bring you to this dialog)
3. click on the Hardware Device tab
4. connect your Ledger Nano S/X to your computer via USB
5. make sure the device is properly unlocked (and already initialized via Ledger Live)
6. click on Import
7. when your Capricoin+ Core wallet says Waiting for device, follow the instructions displayed on your Ledger hardware wallet screen

Your Capricoin+ Core client is now ready to be used in conjunction with your Ledger hardware wallet!

# Usage

## Sending CPS using Ledger

![Sending Screen](https://capricoin.org/images/guide/sending-screen.jpg) ![Transaction confirmation Screen](https://capricoin.org/images/guide/transaction-confirmation-screen.jpg) 

1. open your Capricoin+ Core client containing your Ledger hardware wallet (as set up in the steps above)
2. connect your Ledger hardware wallet to your computer and unlock it using your PIN code
3. select and start the Capricoin+ application on your Ledger hardware wallet
4. click on Capricoin+ Core's Send tab
5. enter your transaction details (CPS amount and destination address)
6. click Send → Yes
7. Capricoin+ Core will prompt you to follow the steps displayed on your Ledger hardware wallet's screen – confirm the transaction on your device if the transaction details are correct