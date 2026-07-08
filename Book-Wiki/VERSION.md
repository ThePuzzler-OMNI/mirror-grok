# Book version

**Current:** **v0.1** (budding) · 2026-07-08  
**Pinned commit:** `45db1edaf559079de1deed4682ed4115be090d60`

Machine-readable registry: [`Core-Framework/BOOK_VERSION.json`](../Core-Framework/BOOK_VERSION.json)

## Source of truth (read this first)

| Role | File | Use for |
|------|------|--------|
| **Canonical LaTeX** | [`Core-Framework/HOG-Model-Full.md`](https://github.com/ThePuzzler-OMNI/mirror-grok/blob/45db1edaf559079de1deed4682ed4115be090d60/Core-Framework/HOG-Model-Full.md) | Editing the book, wiki content, Master Prompt reading |
| **PDF artifact** | [`Core-Framework/HOG_Model___New_Reality_current.pdf`](https://github.com/ThePuzzler-OMNI/mirror-grok/blob/45db1edaf559079de1deed4682ed4115be090d60/Core-Framework/HOG_Model___New_Reality_current.pdf) | Reading/printing the typeset paper (site `read.html`) |

> **Important:** `HOG-Model-Full.md` is **LaTeX** (starts with `\documentclass{book}`), not ordinary Markdown prose. The `.md` extension is historical; treat it as the LaTeX source.

## What the wiki is built from

The **wiki is built from the LaTeX source** (`HOG-Model-Full.md`), not reverse-engineered from the PDF.

- PDF = compiled/exported snapshot for human reading.
- Book-Wiki pages = map + chapter stubs + comment entry points pointing at the LaTeX pin.
- Do not invent a third divergent “wiki-only” body of the book without bumping a version.

## Why versioning

This is a budding project. Comments and Master Prompt runs must know *which* book they refer to.

1. Bump `currentVersion` in `BOOK_VERSION.json` when LaTeX and/or PDF change meaningfully.
2. Record `pinnedCommit` (git SHA) for that release.
3. Optionally tag `book-vX.Y` and add `Core-Framework/releases/vX.Y/README.md`.
4. Point wiki “Current” and Master Prompt pins at that commit until the next bump.

## History

| Version | Date | Commit | Notes |
|---------|------|--------|-------|
| 0.1 | 2026-07-08 | `45db1ed…` | First registered baseline (LaTeX + PDF pair) |
