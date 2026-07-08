# Book version

**Current:** **v0.1** (budding) · 2026-07-08  
**Pinned commit:** `45db1edaf559079de1deed4682ed4115be090d60`

Machine-readable registry: [`Core-Framework/BOOK_VERSION.json`](../Core-Framework/BOOK_VERSION.json)

## Source of truth

| Role | File |
|------|------|
| **Canonical LaTeX** | [`Core-Framework/HOG-Model-Full.md`](../Core-Framework/HOG-Model-Full.md) |
| **PDF artifact** | [`Core-Framework/HOG_Model___New_Reality_current.pdf`](../Core-Framework/HOG_Model___New_Reality_current.pdf) |
| **Prior versions** | [`Archive/`](../Archive/) — dated PDFs and LaTeX snapshots |

## Prior versions (Archive)

When the book goes through revisions, keep outgoing builds in **`Archive/`** with date stamps, e.g.:

- `Archive/HOG_Model___New_Reality_20260525 2.pdf`
- `Archive/HOG-Model-Full-20260525-1.md`

Do **not** overwrite Archive entries. Point the site “current” links only at `Core-Framework/*_current.pdf` and `HOG-Model-Full.md` after a deliberate bump.

Site archive browser: https://onemissionnetworkandinstitute.org/book-archive

## What the wiki is built from

1. **Wikipedia-style article** on the site: `/hog-model` (synopsis of the LaTeX book)  
2. **Book-Wiki/** navigation pages  
3. **Comments** via Discussions  

PDF = typeset snapshot for human reading. Archive = history.

## How to bump a version

1. Copy current LaTeX + PDF into `Archive/` with a date in the filename  
2. Edit `Core-Framework/HOG-Model-Full.md`  
3. Rebuild PDF → `HOG_Model___New_Reality_current.pdf`  
4. Update `BOOK_VERSION.json` (version, pinnedCommit, history)  
5. Optional: tag `book-vX.Y`  
6. Refresh site pin on Master Prompt + wiki article if needed  

## History

| Version | Date | Commit | Notes |
|---------|------|--------|-------|
| 0.1 | 2026-07-08 | `45db1ed…` | First registered baseline; Archive holds May 2026 revision trail |
