# Crypto-Bet

We will build a lottery game today
Each game will have a max number of players and an entry fee
After max number of players have entered the game, one winner is chosen at random
The winner will get maxplayers*entryfee amount of ether for winning the game
BUIDL IT
Initially start by creating a folder named RandomWinnerGame in your computer

To build the smart contract we would be using Hardhat. Hardhat is an Ethereum development environment and framework designed for full stack development in Solidity. In simple words you can write your smart contract, deploy them, run tests, and debug your code.

To setup a Hardhat project, Open up a terminal and execute these commands inside the RandomWinnerGame folder

mkdir hardhat-tutorial
cd hardhat-tutorial
npm init --yes
npm install --save-dev hardhat
In the same directory where you installed Hardhat run:

npx hardhat
Select Create a Javascript project
Press enter for the already specified Hardhat Project root
Press enter for the question on if you want to add a .gitignore
Press enter for Do you want to install this sample project's dependencies with npm (@nomicfoundation/hardhat-toolbox)?
Now you have a hardhat project ready to go!

If you are not on mac, please do this extra step and install these libraries as well :)

npm install --save-dev @nomicfoundation/hardhat-toolbox
and press enter for all the questions.

In the same terminal now install @openzeppelin/contracts as we would be importing Openzeppelin's Contracts

npm install @openzeppelin/contracts
We will also be verifying our contracts, so lets install hardhat etherscan library

npm install --save-dev @nomiclabs/hardhat-etherscan
Lastly we will install the chainlink contracts, to use Chainlink VRF
npm install --save @chainlink/contracts
