# Simple Ronin Explorer

A simple, single-file HTML explorer for contracts on the Ronin blockchain.

## Features

- **No installation required** - just open the HTML file in your browser
- **No dependencies** - everything is contained in a single HTML file
- **Automatic RPC detection** - tries multiple Ronin RPC endpoints
- **Contract verification** - checks if an address is a contract
- **Function discovery** - tests common functions to see what the contract supports
- **Custom function calls** - call specific functions with parameters

## How to Use

1. **Download** the `explorer.html` file to your computer
2. **Open** the file in any modern web browser (Chrome, Firefox, Edge, etc.)
3. The file is pre-configured with your contract address (`0xfB597d6Fa6C08f5434e6eCf69114497343aE13Dd`)

### Simple Steps

1. Click **"Test Connection"** to verify connection to the Ronin blockchain
2. Click **"Check Contract"** to verify the contract exists and get basic info
3. Click **"Test Common Functions"** to discover what functions the contract supports
4. Use the **Custom Function Call** section to try specific functions

## Troubleshooting

If you encounter connection issues:

1. **Try different RPC endpoints** using the dropdown
2. **Check your internet connection** - make sure you're online
3. **Try different browsers** - some browsers handle cross-origin requests differently
4. **Try from a different network** - some networks block blockchain connections

## How It Works

This explorer works by making direct JSON-RPC calls to the Ronin blockchain. It:

1. Tests the connection to different Ronin RPC endpoints
2. Verifies if your address contains contract code
3. Tries calling common contract functions to see what works
4. Allows you to call specific functions with parameters

All of this happens directly in your browser with no server-side components.
