# Colophon (CLPH) — Whitepaper

**A fair-launch proof-of-work coin: every block carries its printer's mark.**

## 1. Introduction

In the old printing shops, the last page of a book carried a small closing
note — the colophon — naming the printer, the date and the place, so that
nobody could pretend the work had come from elsewhere. Anyone who held the
book could turn to the end and read who set it. Colophon is a cryptocurrency
built on the same principle.

Blockchains already give us the mechanical version of that model: an
append-only record that becomes harder to rewrite the longer it stands.
Colophon does not add a new consensus invention on top of that. It applies the
most battle-tested one — proof-of-work — with rules chosen for fairness and
visibility:

- **No premine.** No coins exist before the network starts.
- **No ICO.** No tokens were sold, reserved or auctioned.
- **Fixed, public supply.** Every coin is produced by mining, on a schedule
  that is a function of the block height alone.

## 2. Consensus and mining

Colophon uses **KawPow**, a GPU-oriented, ASIC-resistant proof-of-work
algorithm. KawPow leans on graphics-memory bandwidth, which keeps the barrier
to entry on ordinary NVIDIA and AMD cards and denies purpose-built hardware a
meaningful advantage. Difficulty is retargeted every block to keep the average
block time near its target.

## 3. Parameters

| Parameter        | Value                          |
|------------------|--------------------------------|
| Algorithm        | KawPow (GPU, ASIC-resistant)   |
| Consensus        | Proof-of-Work                 |
| Block time       | 115 seconds                    |
| Block emission   | 28 CLPH                        |
| Halving          | every 520,000 blocks (≈ 1.90 years) |
| Maximum supply   | 28,210,000 CLPH                |
| Premine / ICO    | 0 / 0                          |

## 4. Emission schedule

The emission halves every 520,000 blocks. The first five editions mint:

| Edition | Blocks                 | Emission | Minted      |
|---------|------------------------|----------|-------------|
| 1       | 0 – 519,999            | 28 CLPH  | 14,560,000  |
| 2       | 520,000 – 1,039,999    | 14 CLPH  | 7,280,000   |
| 3       | 1,040,000 – 1,559,999  | 7 CLPH   | 3,640,000   |
| 4       | 1,560,000 – 2,079,999  | 3.5 CLPH | 1,820,000   |
| 5       | 2,080,000 – 2,599,999  | 1.75 CLPH| 910,000     |

Emission keeps halving beyond edition 5 and settles toward the cap of
28,210,000 CLPH without ever passing it.

## 5. Fair launch

The network has no genesis advantage for any participant. The first block
emits under the same rules as every other block of its edition, and the
schedule cannot be changed without a hard fork that the network would have to
choose openly. There is no developer allocation, no treasury premine and no
private sale.

## 6. Verifiability

All source code is published on GitHub under the MIT license. The block
explorer publishes the same parameters stated here, so any user can check the
chain against this document rather than trusting an announcement.

## 7. Note

Colophon is experimental open-source software. This document describes the
design of the network. Verify every download against its published checksum.
