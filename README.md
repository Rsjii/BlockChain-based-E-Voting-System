# E-Voting System Using Cloud-Based Hybrid Blockchain Technology

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [System Architecture](#system-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [Future Work](#future-work)
- [License](#license)

## Introduction

This project implements a secure and efficient online voting system leveraging cloud-based hybrid blockchain technology. It aims to enhance the electoral process by ensuring security, transparency, and accessibility. By integrating blockchain with modern authentication mechanisms, the system ensures the integrity of votes while increasing voter participation.

## Features

- **Secure Voter Registration and Authentication**: Uses JWT and MetaMask for secure login.
- **Blockchain-Based Voting**: Votes are recorded on the Ethereum blockchain using smart contracts.
- **Immutability and Transparency**: Ensures votes cannot be tampered with and provides a transparent voting process.
- **Anonymity**: Maintains voter privacy by decoupling voter identities from their votes.
- **Accessibility**: Allows voters to cast their ballots remotely from any internet-enabled device.
- **Admin Dashboard**: For election administrators to manage elections, candidates, and view results.

## Technologies Used

### Blockchain and Smart Contracts

- **Ethereum Blockchain**
- **Solidity**: For writing smart contracts.
- **Remix IDE**: For smart contract development.
- **Ganache**: Local blockchain for testing.
- **MetaMask**: Ethereum wallet for blockchain interactions.

### Backend

- **Node.js**
- **Express.js**
- **MySQL**
- **JWT (JSON Web Tokens)**

### Frontend

- **React.js**
- **HTML/CSS/JavaScript**

### Cloud Services

- **AWS/Azure/GCP** (Choose one for deployment)

### Security

- **End-to-End Encryption**
- **HTTPS Protocol**

## System Architecture

![System Architecture Diagram](architecture-diagram.png)

*Note: Include an architecture diagram image in your repository.*

## Installation

### Prerequisites

- **Node.js** (v12.x or higher)
- **MySQL** Database
- **MetaMask** Browser Extension
- **Ganache** for local blockchain testing

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/rsjii/blockchain-based-e-voting-system.git

# E-Voting System Using Cloud-Based Hybrid Blockchain Technology

## Installation and Setup

### Backend Setup

1. **Navigate to the backend directory:**
    ```bash
    cd e-voting-blockchain/backend
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Configure environment variables:**
    Create a `.env` file in the backend directory and add the following variables:
    ```makefile
    PORT=5000
    DB_HOST=your_database_host
    DB_USER=your_database_user
    DB_PASSWORD=your_database_password
    DB_NAME=your_database_name
    JWT_SECRET=your_jwt_secret
    ```

4. **Start the backend server:**
    ```bash
    npm start
    ```

### Frontend Setup

1. **Open a new terminal window and navigate to the frontend directory:**
    ```bash
    cd e-voting-blockchain/frontend
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Start the frontend development server:**
    ```bash
    npm start
    ```

### Blockchain Setup

- **Start Ganache** to run a local blockchain.
- **Import accounts** from Ganache into MetaMask.
- **Use Remix IDE** connected to your local blockchain to compile and deploy the `Voting.sol` contract.
- **Copy the contract address** and update it in the frontend configuration.

### Database Setup

1. **Create a MySQL database** using the credentials specified in your `.env` file.
2. **Run the database migration scripts** located in `backend/migrations` to set up the tables.

## Usage

### Access the Application

- Open your web browser and navigate to `http://localhost:3000`.

### Voter Registration

- Click on the "Register" button.
- Fill in the required details and submit the form.

### Voter Login

- Click on the "Login" button.
- Enter your credentials and log in.

### Connect MetaMask

- Ensure MetaMask is installed and connected to the local blockchain network.
- Connect your account when prompted.

### Cast Vote

- Once logged in and connected to MetaMask, navigate to the voting page.
- Select your preferred candidate and submit your vote.

### Admin Operations

- Log in as an admin using admin credentials.
- Manage candidates, monitor the voting process, and view results.

## Project Structure

```plaintext
e-voting-blockchain/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── migrations/
│   ├── app.js
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
├── contracts/
│   ├── Voting.sol
├── migrations/
├── test/
├── README.md
└── package.json
```
## Contributing

Contributions are welcome! Please follow these steps:

1. **Fork the repository**

2. **Create a new branch**

    ```bash
    git checkout -b feature/your-feature-name
    ```

3. **Commit your changes**

    ```bash
    git commit -m "Add your message"
    ```

4. **Push to the branch**

    ```bash
    git push origin feature/your-feature-name
    ```

5. **Create a Pull Request**

## Future Work

- **Mobile Application Development**: Develop a cross-platform mobile app.
- **Advanced Security Features**: Implement AI-based fraud detection.
- **Scalability Improvements**: Optimize for handling large-scale elections.
- **Additional Language Support**: Add multilingual support for wider accessibility.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
