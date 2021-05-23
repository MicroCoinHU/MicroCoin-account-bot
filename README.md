# MicroCoin-account-bot

You can download the JavaScript SDK from here: <br />
https://github.com/MicroCoinHU/MicroCoin-Javacript-SDK

# Installation
First, we install node.js and npm:
```
sudo apt install nodejs npm
```
Then, we make a folder for the program and pull the repos:
```
mkdir account-bot
cd account-bot
git clone https://github.com/Frigyes06/MicroCoin-account-bot
cd MicroCoin-account-bot
git clone https://github.com/MicroCoinHU/MicroCoin-Javacript-SDK
```
Next, we install the dependencies
```
npm install
```
Now, we have to set our private key (in HEX)
```
nano index.js 6
```
Next, the Discord bot's ID
```
nano index.js 104
```
After that, we can start the program:
```
node index.js
```
