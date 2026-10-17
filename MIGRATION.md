# Migration provenance

Date: 2026-10-05.

- Original repository: [bpc-sokoban-demo](https://github.com/JoffeeLin/bpc-sokoban-demo).
- Original snapshot: `1a1f34bb8649d048af4cf1c44426581519ec64c5`; [public pre-migration archive](https://github.com/JoffeeLin/bpc-sokoban-demo/tree/before-repository-split-20261005/tetris).
- Original path: `tetris/`; contents now live at this repository's root.
- Imported files: 182; all Git blob IDs and file modes were verified against the original snapshot.
- Extracted directory history: 184 commits; authors, dates and messages are preserved in the split history. Split commit IDs differ from the original repository.
- Source split tip: `19d85d9e794875a5dba728e4de7f6480f2de23f5`.

The original repository retains its published history, release assets and archive tag. No research source or result was retuned during migration.

The directory history was extracted using [Git subtree split](https://github.com/git/git/blob/master/contrib/subtree/git-subtree.adoc), which preserves the history associated with a directory.

## Second migration: 2026-10-17

- Source repository: [bpc-sokoban-demo](https://github.com/JoffeeLin/bpc-sokoban-demo), source main commit `8736dc115a7de6571d3e86abef8dc0f0ebaa891d`.
- Source prefix: `tetris/`; destination: the matching path at the root of `bpc-tetris`.
- Imported **104 UTF-8 files** (current-best pointer + source/report + 2026-10-06 experiment archives). Every destination Git blob SHA was verified against the source SHA **before** removing old working-tree copies.
- Recovery branch in the source: [backup-before-tetris-extraction-2026-10-17](https://github.com/JoffeeLin/bpc-sokoban-demo/tree/backup-before-tetris-extraction-2026-10-17).
- Recovery branch in the destination: [backup-before-oct6-import-2026-10-17](https://github.com/JoffeeLin/bpc-tetris/tree/backup-before-oct6-import-2026-10-17).
- This second move uses a new import commit rather than a second subtree-history rewrite. Original historical commits remain accessible in the source repository and the backup branch. Only navigation/index files were changed to reflect new paths; experimental C code and results are unchanged.
