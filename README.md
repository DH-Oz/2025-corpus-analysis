# 2025 Corpus Analysis Masterclass (Archive)

Historical archive of the 2025 edition of the Digital Humanities Winter School corpus-analysis masterclass, taught in **R** with **R Markdown**. Co-delivered by Mark Alfano and Brian Ballsun-Stanton.

> **This repository is an archive.** It is preserved as a record of the 2025 course. New course development happens in [`DH-Oz/CorpusAnalysis`](https://github.com/DH-Oz/CorpusAnalysis) (the 2026 Python/Jupyter pivot and beyond).

## Contents

- `20250504 corpusmasterclass{1,2,3a,3b}.Rmd` — the four main session lessons.
- `20250506-corpusmasterclass0.Rmd` — prereq / setup document.
- `20250504-corpusmasterclass{1,2,3a,3b}.html` — rendered HTML of each lesson.
- `nietzsche/` — the working corpus (twenty-three Nietzsche texts, plain-text English translations).
- `*.dic` — custom dictionaries used in the course (`nietzsche.dic`, `macdvirtue.dic`, `nuke.dic`).
- `*.tiff` — example output figures (word cloud, virtue analysis).
- `todo.md` — a glimpse of the original planning notes.

## Bundled download

A single-zip download of the course materials is available on the [Releases page](https://github.com/DH-Oz/2025-corpus-analysis/releases) — convenient for students who want to grab everything without browsing the repo.

## What is NOT included

**LIWC** (`liwcdict.dic`) is a commercial product and is **not** redistributed here, even though the original 2025 course used it. The lesson source code references `liwcdict.dic` in places — that code will not run end-to-end without a licensed LIWC dictionary supplied separately. Contact the instructors if you have a LIWC licence and want to reproduce the LIWC-based portions of the 2025 course.

## Licences

- **Lesson content** (Rmd, HTML, prose, custom dictionaries) — [CC BY-NC 4.0](LICENSE-CONTENT.md).
- **Code** (R chunks, Python scratch files) — [MIT](LICENSE-CODE.md).

## Citation

> Alfano, M. & Ballsun-Stanton, B. (2025). *DH Winter School Corpus Analysis Masterclass* (2025 edition). CC BY-NC 4.0. https://github.com/DH-Oz/2025-corpus-analysis

## Contact

Mark Alfano — [contact TBD]
Brian Ballsun-Stanton — brian.ballsun-stanton@mq.edu.au
