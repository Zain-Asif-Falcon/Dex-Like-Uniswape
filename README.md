# Build your own Decentralized Exchange like Uniswap![Capture](https://user-images.githubusercontent.com/121422342/236197964-d1f608b9-23e3-4072-992c-eb47e8af799d.PNG)
## Steps to build a uniswap project
```
mkdir hardhat-tutorial
cd hardhat-tutorial
npm init --yes
npm install --save-dev hardhat
```
#If you are a Windows user, you'll have to add one more dependency. so in the terminal, add the following command
```
npm install --save-dev @nomicfoundation/hardhat-toolbox
```
#In the same directory where you installed Hardhat run
```
npx hardhat
```
#In the same terminal now install @openzeppelin/contracts as we would be importing Openzeppelin's ERC20 Contract in our Exchange contract
```
npm install @openzeppelin/contracts
```
#First, You would need to create a new next app. Your folder structure should look something like
```
- uniswap
       - hardhat-tutorial
       - my-app
 ```
 #To create this my-app, in the terminal point to DeFi-Exchange folder and type
 ```
 npx create-next-app@latest
 ```
 #Now to run the app, execute these commands in the terminal
 ```
 cd my-app
npm run dev
```
#Open up a terminal pointing atmy-app directory and execute this command
```
npm install web3modal
```
#In the same terminal also install ethers.js
```
npm i ethers@5
```
#Now in your terminal which is pointing to my-app folder, execute
```
npm run dev
```
