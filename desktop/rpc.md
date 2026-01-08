# RPC Endpoints

Configure connections to blockchain networks.

## What is RPC?

RPC endpoints connect Quasarr to blockchain networks. You need them for:
- Checking wallet balances
- Executing transactions
- Interacting with smart contracts

## Adding an Endpoint

1. Click **New Endpoint**
2. Enter a name (e.g. "Ethereum Mainnet")
3. Enter the RPC URL
4. Click **Save**

## Finding RPC URLs

Get RPC endpoints from services like:
- Alchemy
- Infura
- QuickNode
- Ankr

Most services offer free tiers. Create an account to get your URL.

## Testing Connections

### Single Test
Click the ping button next to any endpoint.

### Test All
Click **Ping All** to check every endpoint at once.

## Health Status

| Status | Color | Meaning |
|--------|-------|---------|
| Online | Green | Working normally |
| Slow | Yellow | High latency |
| Offline | Red | Not responding |

## Metrics Shown

- Latency in milliseconds
- Success rate
- Last checked time

## Managing Endpoints

- Click the pencil icon to edit
- Click the trash icon to delete

## Tips

- Add multiple endpoints per network for reliability
- If one endpoint fails, try another
- Check service status pages if all endpoints for a network are down
