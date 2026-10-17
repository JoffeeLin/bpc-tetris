# Tetris October 6 archive — exact duplicate removal

Audit date: 2026-10-17. Scope: only byte-identical Git blobs verified by Git blob identity in the original `JoffeeLin/bpc-sokoban-demo` repository. This is **file deduplication, not deletion of independent scientific conclusions**.

The post-v1.13 dated [research index](post-v1.13/INDEX.md) remains authoritative for these seven experiment groups. The old flat copies were removed; canonical REPORT / RESULTS / SOURCES (and, where present, SHA256 and standalone v1.53 files) remain unchanged in their respective directories.

| Removed duplicate folder (relative to this directory) | Preserved canonical folder |
| --- | --- |
| `binary-world-action-v1.31-v1.33/` | [`post-v1.13/v1.31-v1.33-unified-temporal-residual/`](post-v1.13/v1.31-v1.33-unified-temporal-residual/) |
| `minimal-kernel-v1.25-v1.53/` | [`post-v1.13/minimal-v1.25-v1.53/`](post-v1.13/minimal-v1.25-v1.53/) |
| `minimal-kernel-v1.54-v1.66/` | [`post-v1.13/minimal-v1.54-v1.66/`](post-v1.13/minimal-v1.54-v1.66/) |
| `tetris-reintegration-v1.67-v1.70/` | [`post-v1.13/tetris-reintegration-v1.67-v1.70/`](post-v1.13/tetris-reintegration-v1.67-v1.70/) |
| `scaffold-equivalence-v1.14-v1.24/` | [`post-v1.13/v1.14-v1.24-scaffold-equivalence/`](post-v1.13/v1.14-v1.24-scaffold-equivalence/) |
| `scaffold-equivalence-v1.25-v1.28/` | [`post-v1.13/v1.25-v1.28-medium-equivalence/`](post-v1.13/v1.25-v1.28-medium-equivalence/) |
| `world-action-medium-v1.29-v1.30/` | [`post-v1.13/v1.29-v1.30-world-action-symmetry/`](post-v1.13/v1.29-v1.30-world-action-symmetry/) |

24 completely identical files removed (277,741 bytes of duplicated working-tree data). The surviving blobs' SHA values match the removed counterparts, and Git history / [the source repository's pre-cleanup branch](https://github.com/JoffeeLin/bpc-sokoban-demo/tree/backup-before-tetris-duplicate-cleanup-2026-10-17) preserve the old paths.

**Not deduplicated:** different-version RESULT files with identical output text, where independently named run provenance may matter; `current-best/` quick-start sources and their dated archive copies; rejected experiment frozen input copies; nonidentical negative-control runs. These remain until their dependencies and scientific roles are individually reviewed.
