# Token farm DApp

## Description
- Deploys 2 tokens mDAI and DAPP.
- Allows users to stake mDAI into the smart contract and receive DAPP token as a reward.

## Deployment
Run the repo with the following commands

1. cd into the project folder  
2. Run Ganache  
- `truffle migrate` (fresh run)
- `truffle migrate --reset` (second run)

3. Run the app development server
`npm run start`

4. After user staked, open a new command line and run the issue-token.js script
`truffle exec scripts/issue-token.js`
