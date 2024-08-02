# foundry-f23

- Solidity
- Foundry
  - Avil
  -Forge

***Encrypt Private Key**

```
cast wallet import <defaultKey> --interactive
```

Provide private key to encrpyt private key and a password of choice


View Wallet List

```
cast wallet list
```

```
forge script script/filename.s.sol --rpc-url localhost:8545 --account defaultkey --sender <"address generated after cast import"> --broadcast
```