# Transfers

Move funds between wallets efficiently.

## Two Modes

Use the tabs at the top to switch between modes:
- **Disperse** - Send from one wallet to many
- **Collect** - Gather from many wallets to one

---

## Disperse

Split funds from a source wallet to multiple recipients.

### Setup

1. Select **Disperse** tab
2. Choose a source wallet
3. Select an RPC endpoint for the network

### Adding Recipients

From your wallet group:
1. Select wallets from the available list
2. Use **Select All** for the entire group
3. Click **Add** to include them

### Setting Amounts

- Set individual amounts per recipient
- Or use **Bulk Amount** to apply the same value to all

### Execute

1. Review total amount
2. Check recipient list
3. Click **Execute**

Each transfer creates a separate transaction.

---

## Collect

Gather funds from multiple wallets into one destination.

### Setup

1. Select **Collect** tab
2. Choose a destination wallet
3. Select an RPC endpoint

### Adding Sources

1. Select wallets from the available list
2. Add them to sources

### Amount Options

- **Collect All** - Transfer entire balance (minus gas)
- **Fixed Amount** - Transfer specific amount from each

### Execute

1. Refresh balances first
2. Review total to collect
3. Click **Execute**

---

## Tips

- Refresh balances before any transfer
- Each source wallet needs gas for outgoing transactions
- Start with one test transfer before large batches
