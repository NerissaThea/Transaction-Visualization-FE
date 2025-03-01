# Blockchain Transaction Information Visualization System

## Project Summary
The Blockchain Transaction Information Visualization System is an interactive platform designed to simplify the analysis and exploration of blockchain transactions. It provides users with a graphical interface to visualize wallet interactions, transaction histories, and smart contract behaviors. By transforming complex blockchain data into an intuitive, accessible format, the platform helps users understand transaction patterns, network activities, and identify key players within the blockchain ecosystem.

## Installation

To get started with the project, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/blockchain-transaction-visualization.git
    cd blockchain-transaction-visualization
    ```

2. Install the required dependencies:

    ```bash
    npm install
    ```

3. Start the development server:

    ```bash
    npm start
    ```

4. Open the application in your browser:

    Navigate to `http://localhost:3000` to see the app running.

## Features

- **Interactive Blockchain Graphs**: Visualizes wallet addresses as nodes and transactions as edges. Users can interact with the graph to explore transaction paths and networks.
- **Transaction History**: Displays a detailed transaction table with relevant information such as hash, method, block number, age, sender/receiver wallet addresses, and transaction fee.
- **Wallet Overview**: Shows details like wallet balance, total sent/received amounts, and multichain portfolio values.
- **Search Functionality**: Users can input a wallet address to retrieve detailed information about the wallet and its transaction history.
- **Transaction Details**: Clicking on a transaction edge reveals detailed information such as transaction amount and addresses involved.
- **Pagination & Filtering**: Users can filter and paginate through transaction data for easier exploration.

## Project Results

The system is designed to provide an intuitive and visually engaging interface that makes blockchain data more accessible. It includes:

- **Directed Graph Visualization**: Using React Flow, a dynamic and interactive graph is displayed where nodes represent wallet addresses, and edges represent transactions. Users can click on nodes and edges to explore more detailed information about wallet interactions and transaction flows.
  
- **Transaction History**: A comprehensive table that lists transactions associated with a specific wallet. It supports filtering by transaction method (e.g., Transfer, Claim) and includes pagination for easier navigation.

- **Responsive Design**: The platform is fully responsive, ensuring it works seamlessly across devices of various screen sizes, from desktops to mobile phones.

- **Future Enhancements**: The platform is designed with scalability in mind, allowing for the addition of real-time blockchain data and advanced filtering options in the future.

## Deployment on Vercel

For more detailed information on deploying to the Vercel platform and to see how the web app works, please visit the following link: [https://www.youtube.com/watch?v=9AifhMKtUqw](https://www.youtube.com/watch?v=9AifhMKtUqw).
