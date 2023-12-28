# Ether-MultiSender-Smart-Contract
MultiSender is a simple Ethereum smart contract that allows the owner to send Ether to multiple addresses in a single transaction. It is implemented in Solidity and includes safety features to prevent reentrancy attacks.

FEATURES

1. MultiSend: Send Ether to multiple addresses in a single transaction.
2. Withdrawal: Withdraw the remaining balance from the contract.
3. Ownership Transfer: Easily transfer ownership of the contract to another address.
4. Safety Measures: Includes a noReentrancy modifier to prevent reentrancy attacks.

GETTING STARTED

1. Clone the repository:
git clone https://github.com/devEmkiddo/multisender.git

2. Navigate to the project directory:
 cd multisender

4. Compile the Solidity contract using your preferred development environment.


USAGE

1. Deploy the MultiSender contract to the Ethereum network.
2. Use the deposit function to add Ether to the contract.
3. Execute the multiSendEth function to send Ether to multiple addresses.
4. Withdraw any remaining balance using the withdraw function.
   
SMART CONTRACT DETAILS

- Owner: The address that deploys the contract is the initial owner.
- Modifiers:
- onlyOwner: Restricts certain functions to only the contract owner.
- noReentrancy: Prevents reentrancy attacks by locking during execution.

Events

- Withdrawal: Emitted when the owner withdraws funds from the contract.
- OwnershipTransferred: Emitted when ownership of the contract is transferred.

 Contributions
 
   Contributions are welcome! Feel free to submit issues and pull requests.

License
This project is licensed under the MIT License.

Made with ❤️ by devEMKIDDO
