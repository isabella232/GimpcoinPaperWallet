GimpcoinPaperWallet
===================
Instructions to use the Offline Gimpcoin Paper Wallet Generator

1) Clone or download .zip
2) leave all files where you find them! index.html and photos must be on the same folder
3) open index.html file in browser
4) choose which wallet you want to create
5) create and print it

Instructions to RECEIVE-SPEND coins with a printed Paper Wallet

1) To receive coin simply use a Smartphone App (e.g. Barcode Scanner for Android https://play.google.com/store/apps/details?id=com.google.zxing.client.android&hl=en) to read your address

2) If you want to spend coins stored into paper wallet, you MUST add paper wallet address to a Qt-Wallet (so, to be sure your coins are always safe, the best thing to do is use paper wallets only one time). To add your paper wallet address into a Qt-Wallet simply do this:
  - if qt-wallet is unlocked: go to "Help -> Debug window -> Console Tab" and type "importprivkey <private key         showed on the right side of paper wallet> <label for the address>"
  - if qt-wallet in locked: go as usual into the console tab and type first "walletpassphrase <your passprhase>        <seconds you want to keep wallet unlocked>" (e.g. "walletpassphrase MYWALLETPASSWORD 60").. then type              "importprivkey <private key showed on the right side of paper wallet> <label for the address>"

3) after that, you can see your address into the "Receive Tab" and your new qt-wallet's balance 

This is all.

Donations to develop GIMP OS are appreciated: GVoNv1jCdpX7w5L2wV741mXgVg1s6oXX6G

The GIMPcoin developers
