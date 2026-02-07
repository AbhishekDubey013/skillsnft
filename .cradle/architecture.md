# Architecture

## Dependency Graph

```mermaid
graph TD
  eef56ff1["Stylus-contract (stylus-contract)"]
  c8f520e5["Erc721-stylus (erc721-stylus)"]
  2f3fff28["Erc1155-stylus (erc1155-stylus)"]
  b371f1c1["Smartcache-caching (smartcache-caching)"]
  4bc51bb0["Auditware-analyzing (auditware-analyzing)"]
  c95a8b0e["Dune-nft-floor (dune-nft-floor)"]
  2745e939["Sdk-generator (sdk-generator)"]
  6639bff9["Ipfs-storage (ipfs-storage)"]
  233653bb["Frontend-scaffold (frontend-scaffold)"]
  1e7b3726["Wallet-auth (wallet-auth)"]
  60c9eed4["Chain-data (chain-data)"]
  eef56ff1 --> b371f1c1
  eef56ff1 --> 4bc51bb0
  eef56ff1 --> 233653bb
  c8f520e5 --> 6639bff9
  2f3fff28 --> 6639bff9
  c8f520e5 --> 233653bb
  2f3fff28 --> 233653bb
  c8f520e5 --> c95a8b0e
  c8f520e5 --> 2745e939
  233653bb --> 1e7b3726
  233653bb --> 60c9eed4
```

## Execution / Implementation Order

1. **Stylus-contract** (`eef56ff1`)
2. **Erc721-stylus** (`c8f520e5`)
3. **Erc1155-stylus** (`2f3fff28`)
4. **Smartcache-caching** (`b371f1c1`)
5. **Auditware-analyzing** (`4bc51bb0`)
6. **Dune-nft-floor** (`c95a8b0e`)
7. **Sdk-generator** (`2745e939`)
8. **Ipfs-storage** (`6639bff9`)
9. **Frontend-scaffold** (`233653bb`)
10. **Wallet-auth** (`1e7b3726`)
11. **Chain-data** (`60c9eed4`)
