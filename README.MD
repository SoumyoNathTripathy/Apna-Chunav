# Decentralized Blockchain-based Voting System

This is a decentralized blockchain-based voting system built on Ethereum smart contracts. The system uses web3.js for verifying the KYC of the user using face matching. All the photos and documents are stored on IPFS, and Twilio is used to send confirmation messages.

## Team Leader's LinkedIn Profile
https://www.linkedin.com/in/shubham-kumar-singh-356427206/

## Team Members
Shubham Kumar Singh
Aayush Kumar Singh
Ujjwal Kumar
Soumyo Nath Tripathy

## Deployed Project Website Link
https://apna-chunav-eight.vercel.app/

## Overview of the App

- The app is a secure and transparent way of conducting elections.
- Ethereum smart contracts are used for vote counting and verification.
- This app has mainly two sides one is admin side one is normal voter side.
- The system ensures that only registered users can cast their votes.
- Each user can cast only one vote to prevent fraud.
- KYC verification is done using face matching to ensure that only eligible users can participate in the elections.
- All the photos and documents related to KYC verification are stored on IPFS to ensure that they cannot be tampered with.
- Twilio is used to send confirmation messages to the users after they cast their votes, adding an additional layer of security.

## Structure of the Project

The project consists of two main components: the smart contract and the front-end application. The smart contract is responsible for vote counting and verification. The front-end application is responsible for user authentication, KYC verification, and vote casting.

This project has two sides one is the admin side one is the normal voter side, only the admin side has the ability to verify the add candidate, and verify voter.

The project uses Truffle for compiling and deploying the smart contract. Ganache or any other Ethereum-compatible blockchain can be used for running the local blockchain network.

The front-end application uses web3.js for interacting with the smart contract. The application is built using React. The application uses the face matching API for KYC verification. The photos and documents related to KYC verification are stored on IPFS.

## Tech Stack

The tech stack used in the decentralized blockchain-based voting system is as follows:

- Ethereum: Ethereum is used to build the smart contracts that handle the vote counting and verification.
- Web3.js: Web3.js is used to interact with the smart contracts from the front-end application.
- React: React is used to build the front-end application.
- IPFS: IPFS is used to store the photos and documents related to KYC verification.
- Twilio: Twilio is used to send confirmation messages to the users after they cast their votes.
- Face Matching API: Face Matching API is used for KYC verification.
- Truffle: Truffle is used to compile and deploy the smart contracts to the local blockchain network.
- Ganache: Ganache is used as the local blockchain network for testing the smart contracts.

## Model Deployment

1. Clone the repository.

<pre><div class="bg-black mb-4 rounded-md"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans"><span class="">bash</span><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">git clone https://github.com/sukhendu2002/decentralizedVotingUsingBlockchain.git
</code></div></div></pre>

2. Install the dependencies.

```
npm install
cd server 
npm install 
cd ..
cd client
npm install
cd ..

```

3. Start the local blockchain network using Ganache or any other Ethereum-compatible blockchain.
4. Compile and deploy the smart contract to the local blockchain network.

```
truffle migrate --reset --netwok mumbai
cd server 
npm start
```

open a new terminal

```
cd client
npm start
```

## Demo Screenshots

#### Landing Page

![Screenshot 2023-03-21 094304](https://user-images.githubusercontent.com/76715464/226516378-478a94ef-b842-4505-bdef-01c1fc4d1af0.png)

#### Add a new candidate

![1677394929645](https://user-images.githubusercontent.com/76804228/221397485-dcc9b796-4212-41e3-9d49-0aa21564950a.png)

#### Initialize Voting

![1677394973442](https://user-images.githubusercontent.com/76804228/221397495-aa652c0d-e28a-4efc-a0b6-80a7ff20a7b1.png)

#### Voter Registration page

![1677395069893](https://user-images.githubusercontent.com/76804228/221397502-1a7035a4-2e7a-4e64-8300-1606bf4efbc2.png)

#### Verification page from the Admin side

![1677395387524](https://user-images.githubusercontent.com/76804228/221397507-1ef7944a-259f-45f6-8b99-06da9fe81405.png)

#### Voting page

![1677395441904](https://user-images.githubusercontent.com/76804228/221397511-45ceb9b9-85f8-4b21-9cd8-7f3552352399.png)

#### Result Page

![1677395513220](https://user-images.githubusercontent.com/76804228/221397514-2d5b503a-7988-4096-879f-7ccb11667b69.png)


## Conclusion

The decentralized blockchain-based voting system is a secure and transparent way of conducting elections. The system ensures that only eligible users can participate in the elections and that each user can cast only one vote. The use of face matching for KYC verification and IPFS for storing photos and documents ensures that the system is secure and tamper-proof. The integration of Twilio for sending confirmation messages adds an additional layer of security. The system can be used for conducting elections at various levels, including local, national, and international.
