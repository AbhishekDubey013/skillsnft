# Stylus Contract

| Field | Value |
|-------|-------|
| Type | `stylus-contract` |
| ID | `eef56ff1` |
| Category | contracts |
| Tags | rust, wasm, stylus, arbitrum, custom |
| Description | Rust/WASM smart contract for Arbitrum |

## Configuration

| Setting | Value |
|---------|-------|
| Contract Name | my-contract |
| Contract Instructions | Describe your contract logic here. For example: a simple counter with increment and decrement, or a vending machine with cooldowns. |

## Environment Variables

| Key | Description | Required | Secret | Default |
|-----|-------------|----------|--------|---------|
| `DEPLOYER_PRIVATE_KEY` | Private key for contract deployment | Yes | Yes |  |
| `STYLUS_RPC_URL` | Arbitrum RPC URL (default: Arbitrum Sepolia) | No | No | https://sepolia-rollup.arbitrum.io/rpc |

## Scripts

| Name | Command |
|------|---------|
| `stylus:check` | `cd contracts/counter-contract && cargo stylus check` |
| `stylus:deploy` | `cd contracts/counter-contract && cargo stylus deploy --private-key-path=./.env.key --endpoint="https://sepolia-rollup.arbitrum.io/rpc"` |

## File Structure

This component would generate the following files:

- `docs/STYLUS_CONTRACT_GUIDE.md` (docs)
- `contracts/counter-contract/Cargo.toml`
- `contracts/counter-contract/src/lib.rs`

## Integration Points

**Provides to:**
- Smartcache-caching (`b371f1c1`)
- Auditware-analyzing (`4bc51bb0`)
- Frontend-scaffold (`233653bb`)

