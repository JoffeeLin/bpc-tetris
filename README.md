# BPC Tetris

C experiments, source snapshots and evidence for learning Tetris dynamics and operation through BPC.

This is the dedicated home for BPC Tetris research. The 2026-10-05 split preserved the earlier directory history; the 2026-10-17 import moved the remaining 2026-10-06 experiments from the Sokoban repository after byte-for-byte verification. See [migration provenance](MIGRATION.md).

## Current promoted world-model checkpoint (2026-10-06)

**Binary World-Fit v1.13** — controlled 15×20 binary-screen next-state prediction, with 8 frozen long-rollout seeds totaling **312,839/312,839 exact visible transitions**. It is **not** evidence of BPC learning autonomous Tetris play. The frozen field binary used by some evaluations is not included in the recovered source bundle.

- [Current best pointer](CURRENT_BEST.md) · [promoted source and report](current-best/README.md)
- [2026-10-06 scaffold-deletion experiments](research-2026-10-06/00_INDEX.md)
- [Post-v1.13 negative/partial mechanism research](research-2026-10-06/post-v1.13/INDEX.md)
- [Exact-duplicate audit](research-2026-10-06/DEDUP.md)

## Earlier experiments (2026-10-05)

- [2026-10-05 research index](research-2026-10-05/00_INDEX.md): the development sequence and recorded checkpoint boundaries.
- [Binary World-Fit v0.39–v0.40b](research-2026-10-05/binary-worldfit-v0.39-v0.40b/REPORT.md): the **2026-10-05** index's promoted world-fitting checkpoint, v0.40b (superseded by v1.13).
- [v0.41–v0.43 scaffold audit](research-2026-10-05/binary-worldfit-v0.41-v0.43/REPORT.md): later pilot, partial and negative results.
- [External autoplay verification](research-2026-10-05/autoplay-verification-v0.25b/REPORT.md): world-model verification under an external player.
- [Minimal v0.6](minimal-v0.6/README.md): an existing standalone C mechanism check.
- [Migration provenance](MIGRATION.md): original snapshot and preserved history.

These are research checkpoints with different interfaces and assumptions. World fitting, externally controlled play and learned autonomous operation retain the distinctions in their reports.

## Run the standalone check

From the repository root, with a C11 compiler:

```sh
cc -std=c11 -O2 -Wall -Wextra -Werror minimal-v0.6/bpc_tetris_minimal_v06_standalone.c -o /tmp/bpc-tetris-minimal-v06
/tmp/bpc-tetris-minimal-v06
```

This executes the archived recursive hard-drop mechanism check. Other versions retain their own source/dependency instructions and verification records.

## Related repositories

- [BPC Sokoban](https://github.com/JoffeeLin/bpc-sokoban-demo): Sokoban code, experiments and demonstrations.
- [BPC General Intelligence](https://github.com/JoffeeLin/BPC-General-Intelligence): general theory and query-function research; access requires permission because the repository is private.

License: [MIT](LICENSE).
