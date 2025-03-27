# Blockchain Certificate Verification Smart Contract
##Overview

This Aptos Move smart contract provides a secure and transparent mechanism for verifying and issuing blockchain-based certificates. The contract ensures that only verified institutions can issue certificates, adding an extra layer of trust and authenticity to the certification process.

## Features

- Certificate Issuance
- Institution Verification
- Immutable Certificate Records
- Access Control Mechanisms

## Contract Structure
![image](https://github.com/user-attachments/assets/4267e62f-a1dd-46f3-a74a-92ad494e26c9)

### Structs

1. `Certificate`
   - Stores certificate details including:
     - Holder's address
     - Issuing institution
     - Certificate title
     - Issued date
     - Verification status

2. `VerifiedInstitutions`
   - Maintains a list of verified institutions

## Functions

### 1. `issue_certificate()`
- Allows verified institutions to issue certificates
- Checks institution verification before certificate creation
- Stores certificate on the blockchain

### 2. `add_verified_institution()`
- Enables module admin to add new verified institutions
- Provides access control for institution verification

## Prerequisites

- Aptos Blockchain
- Move Compiler
- Aptos CLI

## Installation

1. Compile the smart contract
2. Deploy to the Aptos blockchain
3. Initialize verified institutions


## License

["0x30466c21b4c048a79b9cc469b901be9c87581aa0782820e2d54a5081d4123fae"]
![image](https://github.com/user-attachments/assets/d8df17a7-a742-4d32-98a7-2e843e28bb6a)


## Contributing

Contributions are welcome. Please submit pull requests or open issues on the project repository.
