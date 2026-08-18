# Transparency

Colophon is built around a simple rule: nothing is printed off-record.
Everything that defines the network is published, and nothing is advertised
before it exists.

## What is public

- **Source code** — the wallet and this site are on GitHub under the MIT
  license. Anyone can inspect, build, and reproduce them.
- **Parameters** — the emission schedule, block time, halving points and cap
  are published in the whitepaper, on the site, and on the block explorer.
- **Downloads** — every archive is published with its SHA-256 checksum, and
  the checksum is repeated on the product page so a single altered page cannot
  silently swap the binary.
- **Roadmap** — the explorer's roadmap column shows only what is actually
  released or in progress. Planned items are marked as such.

## What is not done here

- No announcements of features that do not exist yet.
- No private allocations, founder wallets, or pre-mined coins — the launch is
  even by construction.
- No unverifiable claims about the network's state; the chain itself is the
  authority, and the explorer reads from it.

## How to check

1. Compare the numbers on the download page with the whitepaper and the
   explorer.
2. Verify the SHA-256 of any downloaded archive.
3. Read the source, or build the wallet yourself from source and compare the
   binary's checksum.

If something on this site contradicts the chain, the chain wins. Report any
such discrepancy through the repository.
