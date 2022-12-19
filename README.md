# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```

## Notes

To deploy contract to Goerli:
```shell
npx hardhat run scripts/deploy.js --network goerli
```
To verify the contract on etherscan:
```shell
npx hardhat verify <ADDRESS> --network goerli
```

### Deployed at
Goerli:
0x7c501F5f0A23Dc39Ac43d4927ff9f7887A01869B
0xd0A610E26732aA01960BE87598106240a93b6595