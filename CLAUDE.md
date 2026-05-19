# 2025 Corpus Analysis Masterclass — Archive

Last verified: 2026-05-19

## What this repo is

A **historical archive** of the 2025 R/Rmd edition of the DH Winter School corpus-analysis masterclass. Authors: Mark Alfano (first author) and Brian Ballsun-Stanton.

The archive captures the **full 2025 teaching arc** — the originally-scheduled classes (May 2025) plus the post-class lessons taught in June 2025 (Day 4, TF-IDF, DictionaryBuilder, FirstWordcloud). The post-class additions were folded in via `v2025.1` after the initial `v2025` release was already cut.

Current course development happens in `DH-Oz/CorpusAnalysis` (Python/Jupyter pivot). Do not add **2026-or-later** pedagogical content here — that belongs in `CorpusAnalysis`. Fix-in-place is acceptable for typos, broken links, or licence-compliance issues. The archive should otherwise stay as the 2025 course was delivered.

## Boundaries

- **Never commit**: any LIWC dictionary (`liwcdict.dic`, `LIWC*.dic`, etc.). The 2025 course used LIWC; the archive deliberately does not redistribute it.
- **Never commit**: the third-party PDF corpus referenced by the post-class TF-IDF / DictionaryBuilder lessons (`pdfs/`, `Tarnowski_phdthesis.pdf`). Those are other authors' work. The lesson `.Rmd` files reference them, but readers must supply their own corpus to re-run. See README "What is NOT included".
- **Never commit**: `kwic_output/` or `kwic.zip` — KWIC CSVs derived from the third-party PDFs above. Distributing them would re-distribute short excerpts of those papers.
- **Do not "improve" lesson content** — this is a historical record, not a living document.
- **Preserve the `.Rmd` files as the canonical lesson source**; if rendered HTML drifts, re-render rather than hand-editing.

## Related repos

- `DH-Oz/CorpusAnalysis` — the 2026+ Python/Jupyter living document and the place where new development goes.

## Distribution

- Repo is public on GitHub.
- The course materials are distributed via GitHub's auto-generated `Source code (zip)` on the `v2025` release. LIWC and the third-party PDF corpus are excluded by `.gitignore`, so they're absent from the auto-archive automatically — no custom asset upload is needed. When amending the archive (e.g. folding in post-class content), force-move the `v2025` tag rather than cutting a new tag.
