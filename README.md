# Election - DAPP
With blockchain voting, issues regarding voter confidence, transparency and accessibility could be solved in future elections.

Reference: https://www.dappuniversity.com/articles/the-ultimate-ethereum-dapp-tutorial

Follow the steps below to download, install, and run this project.

## Dependencies
Install these prerequisites to follow along with the tutorial. See free video tutorial or a full explanation of each prerequisite.

**NPM**: https://nodejs.org

**Truffle**: https://github.com/trufflesuite/truffle

**Ganache**: http://truffleframework.com/ganache/

**Metamask**: https://metamask.io/

Step 1. Clone the project

git clone https://github.com/KShivanipai/Crypto-Wave.git

Step 2. Install dependencies

$ cd election

$ npm install

Step 3. Start Ganache

Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance. See free video tutorial for full explanation.

Step 4. Compile & Deploy Election Smart Contract

$ truffle migrate --reset You must migrate the election smart contract each time your restart ganache.

Step 5. Configure Metamask

See free video tutorial for full explanation of these steps:

Unlock Metamask

Connect metamask to your local Etherum blockchain provided by Ganache.

Import an account provided by ganache.

Step 6. Run the Front End Application

$ npm run dev Visit this URL in your browser: http://localhost:3000


## Features:
The features which we have incorporated in our project are given below:

**Admin**

1.Can add voters

2.End the election

3.Can see the candidates vote count 

4.Can Vote only once

**Voters**

1.Can see the candidates vote count

2.Can Vote only once

**Users with no access to vote**

1.Can see the candidates vote count 

2.Cannot vote

**UI**

1.Live/ complete tag near Election Results based on election status (sets to complete when admin “ends the election”)

2.Form Visibility to select the candidates based on whether the voter has voted/yet to vote.

3.When connected to admin wallet, an extra section to “add voters” & “end election”



