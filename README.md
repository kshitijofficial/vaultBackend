# CryptedVaultYT
## Crypted IPFS Vault using MERN Stack and Blockchain

### Overview
This project implements a crypted IPFS vault using the MERN (MongoDB, Express.js, React.js, Node.js) stack along with blockchain technology. The vault allows users to securely store files on the IPFS network while encrypting the data and managing access through blockchain-based and JWT authentication.

### Features
- User authentication using blockchain technology for enhanced security.
- Upload encrypted files to the IPFS network and store their encrypted hashes on the blockchain.
- View and manage uploaded files within the web interface.
- User-friendly interface built with React.js for seamless interaction.

### Technologies Used
- **MongoDB**: Database to store user data and encryption key.
- **Express.js**: Web application framework for Node.js, used to handle server-side logic.
- **React.js**: JavaScript library for building user interfaces, used for the front-end.
- **Node.js**: JavaScript runtime environment used to run the server-side code.
- **IPFS (InterPlanetary File System)**: Peer-to-peer network for storing and sharing files, used for storing encrypted files.
- **Blockchain**: Used for authentication and storing file metadata securely.

### Setup Instructions
1. Step 1: Clone the repository: https://github.com/kshitijofficial/cryptedVaultYT.git
2. Step 2: Setup Server Environment Variables
Navigate to the server directory:
cd cryptedVaultYT/server

Create a new .env file in the server directory with the following entries. These environment variables will be used in config/serverConfig.js.

MONGODB_URL=your_mongodb_url
PORT=3000
JWT_SECRETKEY=your_jwt_secret_key
PINATA_APIKEY=your_pinata_api_key
PINATA_SECRETKEY=your_pinata_secret_key

Replace your_mongodb_url, your_jwt_secret_key, your_pinata_api_key, and your_pinata_secret_key with your actual MongoDB URL, JWT secret key, Pinata API key, and Pinata secret key respectively.

3. Step 3: Start the Server
Run the server using npm:
npm start

Step 4: Setup Client Environment
cd client

Step 5: Deploy your smart contract (ipfsHashStorage.sol) and change the contract address in utils/connectWallet.js

Step 6: Start the Client
Run the client using npm:
npm run dev

Additional Link
You can also visit sepolia-faucet.pk910.de for sepolia faucet.


