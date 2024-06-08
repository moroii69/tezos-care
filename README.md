# Charity Blockchain Project

## Introduction

This project aims to tackle the challenges faced by charities in ensuring security and accessibility in their operations. Charities often grapple with transparency issues, hindering their ability to effectively manage funds and engage with stakeholders. By leveraging blockchain technology, this project seeks to offer a solution that ensures transparency, security, and accessibility for both charities and donors.

## Problem Statement

Existing platforms fail to provide the necessary security and accessibility for charities to operate effectively. Transparency remains a pressing concern, as individuals have the right to know how charitable funds are utilized. Moreover, current applications often lack accessibility for smaller organizations and lack user-friendly interfaces.

## Project Requirements

### Solidity Web3
- Utilize Solidity for contract development, offering inheritance properties and facilitating multiple level inheritance.

### Metamask
- Integrate MetaMask to provide users with an easy-to-use and secure wallet service.

### Node.js
- Employ Node.js as the backend to record transactions, facilitate communication between applications, and integrate with the frontend.

### Ganache
- Utilize Ganache to provide a GUI-based local Ethereum blockchain development environment for deploying and testing contracts.

## Project Workflow

1. **Metamask Connection**: Users must connect their MetaMask wallet to the application for any transaction.
   
2. **Ganache RPC Server**: A Ganache RPC Server is initiated with MetaMask as the wallet, utilizing a Node.js interface.
   
3. **Storage of Charity and Organization Details**: Charity and organization details are stored within the application, with a hash value generated for each entry.
   
4. **Transaction Execution**: Transactions between organizations and charities are executed, with a unique transaction hash generated for each transaction.
   
5. **Block Creation and Mining**: Upon completion of transactions, a block is created, and all transactions are updated when mined by the user.



## Project Setup

1. Clone the Repository:

Use Git to clone the project repository from GitHub or your preferred version control system. 

```
git clone https://github.com/moroii69/tezos-care.git
```
Change your current directory to the project directory you just cloned.

```
cd charity-blockchain-project
```
3. Install Dependencies:

Use npm to install the necessary dependencies listed in the project's `package.json` file.

```
npm install
```

4. (Optional) Environment Variables:

Some projects may require specific environment variables to be configured before running the application. Refer to the project documentation for details on any necessary environment variable setup.


5. Start the Application:


Once the dependencies are installed and any environment variables are configured, you can start the application.
```
npm start
```


6. Access the Application:

The application will usually be accessible through your web browser by navigating to a specified URL (often ``http://localhost:3000`` unless configured otherwise). Refer to the project documentation for the exact URL.



## Additional Notes
- Verify that all dependencies are installed successfully without errors during the ``npm install`` step.
- Consult the project documentation for any further configuration steps specific to the application's functionality.
- Consider security best practices when deploying the project to a production environment.


## License

This project is licensed under the Apache License, Version 2.0. You may not use this file except in compliance with the License. You may obtain a copy of the License at [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0). See the License for the specific language governing permissions and limitations under the License.
