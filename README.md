# My guide on solving Ethernaut CTF with Foundry

### Resources used: [Foundry](https://book.getfoundry.sh/), [RealJonnyTime](https://youtube.com/playlist?list=PLKXasCp8iWpjYKwk0hcdVDVZlpW_NGEYS&si=hcWDR5dG9yokcxz9), [Smart contract Programmer](https://youtube.com/playlist?list=PLO5VPQH6OWdWh5ehvlkFX-H3gRObKvSL6&si=Nve3OhqRdwtRREKr).

Challenges Solution:
[Hello Ether](https://github.com/icis-04/Ethernaut-solitions/blob/main/HelloEther.md)
[Fallback](https://github.com/icis-04/Ethernaut-solitions/blob/main/Fallback.md)
[Fallout](https://github.com/icis-04/Ethernaut-solitions/blob/main/Fallout.md)
[Coin Flip](https://github.com/icis-04/Ethernaut-solitions/blob/main/CoinFlip.md)
[Telephone](https://github.com/icis-04/Ethernaut-solitions/blob/main/Telephone.md)
[Token](https://github.com/icis-04/Ethernaut-solitions/blob/main/Token.md)
[Delegation](https://github.com/icis-04/Ethernaut-solitions/blob/main/Delegation.md)
[Force](https://github.com/icis-04/Ethernaut-solitions/blob/main/Force.md)
[Vault](https://github.com/icis-04/Ethernaut-solitions/blob/main/vault.md)

## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
