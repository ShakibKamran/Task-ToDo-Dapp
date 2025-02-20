# Decentralized To-Do Application

## Overview
This is a decentralized To-Do application that allows users to manage their tasks using blockchain technology. The application interacts with a smart contract deployed on the blockchain to store and retrieve tasks securely.

## Features
- Add tasks to the blockchain
- View all tasks stored on the blockchain
- Mark tasks as finished
- Connect with MetaMask for wallet authentication

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Blockchain:** Ethereum, Solidity, Ethers.js
- **Smart Contract Deployment:** Foundry

## Prerequisites
Before running this project, ensure you have the following installed:
- **Node.js** (latest version recommended)
- **Metamask Extension** installed in your browser
- **Foundry** for smart contract deployment
- **Ethereum Test Network** (like Sepolia, Volta, etc.)

## Installation and Setup
1. **Clone the repository:**
   ```sh
   git clone https://github.com/ShakibKamran/Task-ToDo-Dapp.git
   cd Task-ToDO-Dapp
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Create a `.env` file** in the project root and add the following environment variables:
   ```sh
   PRIVATE_KEY=<your-private-key>
   API_URL=<your-rpc-endpoint>
   CONTRACT_ADDRESS=<your-deployed-contract-address> if your using testnet you can past it on index file.
   ```

4. **Run the application:**
   ```sh
   node index.mjs
   ```

## Smart Contract
The smart contract is written in Solidity and deployed on the blockchain. It includes functions to:
- Add tasks
- Retrieve all tasks
- Get a specific task
- Mark a task as finished

## Usage
1. **Open the application** in your browser: `http://localhost:3000`
2. **Connect MetaMask** by clicking the connect button.
3. **Add tasks** through the UI.
4. **View all tasks** stored on the blockchain.
5. **Mark a task as finished**.

## Folder Structure
```
- /out               # Compiled contract output
- /public            # Frontend HTML, CSS, JavaScript files
- /server.mjs        # Express.js backend
- /main.mjs          # Blockchain interaction logic
- .env               # Environment variables
```

## Troubleshooting
- Ensure your MetaMask wallet is connected to the correct test network.
- Check `.env` for correct API and contract details.
- If smart contract transactions fail, verify gas fees and wallet balance.

## License
This project is licensed under the MIT License.

## Author
Developed by [Shakib Kamran].

