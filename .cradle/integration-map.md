# Integration Map

How components connect and what data flows between them.

### Stylus-contract --> Smartcache-caching

- **Source**: Stylus-contract (`eef56ff1`)
  - Output ports: Contract Guide (any)
- **Target**: Smartcache-caching (`b371f1c1`)
  - Input ports: Contract Input (contract)

### Stylus-contract --> Auditware-analyzing

- **Source**: Stylus-contract (`eef56ff1`)
  - Output ports: Contract Guide (any)
- **Target**: Auditware-analyzing (`4bc51bb0`)
  - Input ports: Contract Input (contract)

### Stylus-contract --> Frontend-scaffold

- **Source**: Stylus-contract (`eef56ff1`)
  - Output ports: Contract Guide (any)
- **Target**: Frontend-scaffold (`233653bb`)
  - Input ports: Contract ABI (contract), Network Config (config)

### Erc721-stylus --> Ipfs-storage

- **Source**: Erc721-stylus (`c8f520e5`)
  - Output ports: NFT Contract (contract)
- **Target**: Ipfs-storage (`6639bff9`)
  

### Erc1155-stylus --> Ipfs-storage

- **Source**: Erc1155-stylus (`2f3fff28`)
  - Output ports: Multi-Token Contract (contract)
- **Target**: Ipfs-storage (`6639bff9`)
  

### Erc721-stylus --> Frontend-scaffold

- **Source**: Erc721-stylus (`c8f520e5`)
  - Output ports: NFT Contract (contract)
- **Target**: Frontend-scaffold (`233653bb`)
  - Input ports: Contract ABI (contract), Network Config (config)

### Erc1155-stylus --> Frontend-scaffold

- **Source**: Erc1155-stylus (`2f3fff28`)
  - Output ports: Multi-Token Contract (contract)
- **Target**: Frontend-scaffold (`233653bb`)
  - Input ports: Contract ABI (contract), Network Config (config)

### Erc721-stylus --> Dune-nft-floor

- **Source**: Erc721-stylus (`c8f520e5`)
  - Output ports: NFT Contract (contract)
- **Target**: Dune-nft-floor (`c95a8b0e`)
  

### Erc721-stylus --> Sdk-generator

- **Source**: Erc721-stylus (`c8f520e5`)
  - Output ports: NFT Contract (contract)
- **Target**: Sdk-generator (`2745e939`)
  

### Frontend-scaffold --> Wallet-auth

- **Source**: Frontend-scaffold (`233653bb`)
  - Output ports: App Context (config)
- **Target**: Wallet-auth (`1e7b3726`)
  

### Frontend-scaffold --> Chain-data

- **Source**: Frontend-scaffold (`233653bb`)
  - Output ports: App Context (config)
- **Target**: Chain-data (`60c9eed4`)
  
