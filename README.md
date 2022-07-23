# smartcontract-starter


![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Yarn](https://img.shields.io/badge/yarn-%232C8EBB.svg?style=for-the-badge&logo=yarn&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Mocha](https://img.shields.io/badge/-mocha-%238D6748?style=for-the-badge&logo=mocha&logoColor=white)

## Description
this starter smartcontart with typscripts using hardhat generator [Read more about hardhat](https://hardhat.org/hardhat-runner/docs/getting-started#overview).

## Features

##### Integration testing
- mocha
- chai

## Requirements

- node >= 14 
- npm >= 6 
- typescript >= 4.0
(we recommend to use yarn)


## Project skeleton
```
.
├── artifacts
|   |── build-info
|   |── contracts
|   |── cache
|   |   |── solidity-files-cache.json
|   |── contracts
|   |   |── morgan.sol
|   |── scripts
|   |   |── deploy.ts 
|   |── test
|   |   |── test.ts
|── .gitignore
|── hardhat.config.ts
|── package.json
|── README.md
|── yarn.lock  
```
### Development
```bash
    yarn add typescript
```

### Testing
To run unit test:
```bash
npx hardhat test
```