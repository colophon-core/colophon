# Mining Colophon (CLPH)

Colophon uses **KawPow** — a GPU-oriented, ASIC-resistant proof-of-work
algorithm. Ordinary NVIDIA and AMD graphics cards are the target hardware;
purpose-built ASICs gain no meaningful advantage.

## What you need

- A Colophon address (generate one in the wallet).
- A recent NVIDIA or AMD GPU.
- A KawPow miner binary (e.g. a TeamRedMiner or LolMiner build with KawPow
  support).
- A pool endpoint for CLPH, or your own node for solo mining.

## Steps

1. Install and start the wallet, then create an address.
2. Configure the miner with the pool address, your worker name, and your
   Colophon address as the payout target.
3. Start the miner and watch the shares land.
4. Blocks and rewards appear on the block explorer once the network is live.

## Example invocation

```text
miner --algo kawpow --server pool.example.com:port --user YOUR_CLPH_ADDRESS.worker
```

Replace the pool endpoint and address with the real ones for your chosen pool.
Pools that list CLPH will publish their own endpoints.

## Solo mining

Solo mining runs against your own node. It needs a full node synced to the
network and the same KawPow miner pointed at `127.0.0.1:port`. Solo mining
pays the full block emission when you find a block, but finds blocks far less
often than pooled mining.

## Difficulty

Difficulty is retargeted every block to hold the average block time near
115 seconds. Hashrate is measured across the whole network; there is no
per-pool difficulty setting published here.

## Note

Mining consumes electricity and produces heat. Set realistic expectations:
rewards follow the published schedule, and nothing on this page is advice of
any kind.
