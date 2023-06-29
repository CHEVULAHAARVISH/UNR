# nUSD Contract Interaction

Welcome to the nUSD Contract Interaction project! This project provides a user-friendly web interface for interacting with the nUSD contract on the Ethereum blockchain. With this interface, you can conveniently deposit Ether and redeem nUSD tokens.

## Overview

The nUSD contract allows users to deposit Ether and receive an equivalent amount of nUSD tokens in return. These nUSD tokens can later be redeemed for Ether, converting them back to their original value. The contract also keeps track of the nUSD token balance for each user.

## Implementation

The project consists of a Solidity smart contract (`UNREAL.sol`) and a web interface (`index.html` and `app.js`). The smart contract defines the nUSD token functionality, including depositing, redeeming, and maintaining the balance. The web interface connects to the contract and provides a user-friendly way to interact with it.

### Assumptions

- The project assumes that users have MetaMask or a compatible Ethereum wallet installed on their web browser.

- The exchange rate is set to 3 nUSD tokens for every 1 ETH deposited. This value can be modified in the contract.

## Remote Hosted Link

You can access the remotely hosted nUSD Contract Interaction project by visiting the following link:

Project Link: https://chevulahaarvish.github.io/UNR/

Feel free to explore and interact with the nUSD contract using the remote interface!

## How to Run the Project

To run the project locally, follow these steps:

1. Clone the project repository:

   ```bash
   git clone https://github.com/CHEVULAHAARVISH/UNR.git
   ```

2. Navigate to the project directory:

   ```bash
   cd UNR
   ```
3. Open the vscode editor and hit live server(add install live serveer if you dont have that extension. ) .

4. Open the `index.html` file in your web browser.

5. Connect your wallet by clicking the "Connect Wallet" button. Grant the necessary permissions when prompted.

6. Your nUSD token balance will be displayed in the "Balance" section.

7. To deposit Ether, enter the desired amount in Ether (ETH) in the "Deposit Ether" input field and click the "Deposit" button.

8. To redeem nUSD tokens, enter the desired amount in nUSD tokens in the "Redeem nUSD" input field and click the "Redeem" button.

9. The balance will be updated periodically to reflect any changes in your nUSD token balance.

**Note:** Make sure you have an active internet connection and the MetaMask extension (or a compatible Ethereum wallet) installed and configured correctly.

## Additional Notes

- The project uses the ethers.js library to interact with the nUSD contract. The library is loaded from a CDN.
- The design and styling of the web interface can be customized by modifying the `styles.css` file to suit your preferences.
- Error handling and validation can be enhanced for production use to handle edge cases and provide better user feedback.
- The project automatically updates the nUSD token balance every 5 seconds. You can modify the update interval in the `app.js` file if desired.



Repository Link: [https://github.com/CHEVULAHAARVISH/UNR.git](https://github.com/CHEVULAHAARVISH/UNR.git)

