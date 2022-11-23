# Opyn Crab Netting contest details

- 25,000 USDC main award pot
- Join [Sherlock Discord](https://discord.gg/MABEWyASkp)
- Submit findings using the issue page in your private contest repo (label issues as med or high)
- [Read for more details](https://docs.sherlock.xyz/audits/watsons)
- Starts November 23, 2022 15:00 UTC
- Ends November 30, 2022 15:00 UTC

# Resources

- [Crab Netting](https://opynopyn.notion.site/Crab-Netting-Blurb-d4ce8a3c75694c54af03b3997a70be0c)
- [Twitter](https://twitter.com/opyn_)
- [Website](https://www.opyn.co/)

# On-chain context


```
DEPLOYMENT: [goerli](https://goerli.etherscan.io/address/0xf3e40abf4c06b9454440cb93d42e60de5e67db2a)
ERC20: [Sqth, Crab, WETH, USDC]
ERC721: uni-V3 if you lp for sqth-eth
ADMIN: [contract is ownable; and there are some onlyOwner functions]
```

# Tests

Install [forge](https://book.getfoundry.sh/getting-started/installation)
open .env and add in your API for your RPC_ENDPOINT
`cd crab-netting`
`forge test`

# Audit scope

The following contracts are in scope
1. CrabNetting.sol (its interfaces)
and its dependencies
CrabStrategyV2.sol
Controller.sol

# About Opyn

Opyn builds DeFi-native derivatives and options infrastructure. Opyn built DeFi's first options protocol and has since grown into a flourishing product ecosystem and global community that has collectively traded more than $4 billion of notional volume across 45,000+ trades, and we're just getting started.

