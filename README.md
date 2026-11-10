# Pump Fun Pills: round files

Every NFT draw on pfpills.com publishes its files here, so anyone can check it.

For round N:

- `round-N.prepublish.json`: the record written before the draw is accepted, naming the holder file and its fingerprint.
- `round-N.bundle.json.gz`: the holder file: every qualifying wallet with its tokens, holding times and points.
- `round-N.report.json`: the result: the randomness used, the 20 winners and the transactions.

The fingerprint of the holder file is locked on Solana before the draw. The Round proof page on https://www.pfpills.com/#fair downloads these files, checks them against the chain and recomputes the winners in your browser.

These files are written by the project's draw service. They are checked against the chain, not trusted: a changed file does not match the fingerprint on chain.

No round has been drawn yet: files appear here after launch.
