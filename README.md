# nova-submissions

Encrypted submission blobs from the SN68 elite miner.

Each `.txt` file is a drand-timelocked encrypted submission, referenced from
the on-chain commitment for the corresponding epoch. Filenames are SHA-256
hash prefixes of their content.

This repo is **append-only**; old submissions are kept for validator audit.
