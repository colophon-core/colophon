# Colophon wallet guide

The wallet is the official way to hold CLPH and to take part in the network.
It manages your keys locally, builds and signs transactions, and shows your
balance against the chain.

## Install

1. Download the archive for your platform from the official site.
2. Compare its SHA-256 against the published checksum before running anything.
   On Windows PowerShell:

   ```powershell
   Get-FileHash .\colophon-wallet-windows-0.1.0.zip -Algorithm SHA256
   ```

   The output must match the value published on the download page.
3. Extract the archive and run the wallet.

## First run

- The wallet generates a fresh address and a recovery phrase on first start.
- Write the recovery phrase down and store it offline. It is the only way to
  restore the wallet. Never share it, never type it into a website, and never
  take a photo of it.

## Sending and receiving

- **Receive:** your address is shown on the main screen. Anyone can send CLPH
  to it.
- **Send:** enter a destination address and an amount. The wallet estimates the
  fee and signs the transaction locally.

## Backups

- The recovery phrase is the backup. Keep it in at least two places, offline.
- A wallet file may also be exported; guard it as carefully as the phrase.

## Note

The wallet is experimental open-source software. It is your responsibility to
keep the recovery phrase safe — losing it means losing access to the coins,
and there is no central party to ask.
