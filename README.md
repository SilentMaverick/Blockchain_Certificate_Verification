# Blockchain Certificate System

A full-stack application for issuing and verifying blockchain-based certificates using the Aptos blockchain and Petra wallet.

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Petra Wallet browser extension
- Aptos CLI (for smart contract deployment)

## Project Structure

```
.
├── frontend/           # React frontend application
├── backend/           # Node.js backend server
└── sources/          # Aptos smart contracts
```

## Setup Instructions

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

The frontend will be available at `http://localhost:3000`

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the backend directory with the following variables:
   ```
   PORT=3001
   APTOS_NODE_URL=https://fullnode.devnet.aptoslabs.com
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

The backend will be available at `http://localhost:3001`

### Smart Contract Deployment

1. Make sure you have the Aptos CLI installed and configured
2. Deploy the smart contract:
   ```bash
   aptos move publish
   ```

## Usage

1. Install the Petra Wallet browser extension
2. Connect your Petra wallet to the application
3. Use the form to issue new certificates
4. Verify certificates using the certificate ID

## Features

- Issue blockchain-based certificates
- Verify certificate authenticity
- Petra wallet integration
- Modern and responsive UI
- Secure backend API

## Security Considerations

- Always verify the smart contract address before interacting
- Keep your private keys secure
- Use HTTPS in production
- Implement proper input validation
- Follow security best practices for API endpoints

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 