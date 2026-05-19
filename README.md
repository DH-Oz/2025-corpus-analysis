# 2025 Corpus Analysis Masterclass (Archive)

Historical archive of the 2025 edition of the Digital Humanities Winter School corpus-analysis masterclass, taught in **R** with **R Markdown**. Co-delivered by Mark Alfano and Brian Ballsun-Stanton.

> **This repository is an archive.** It is preserved as a record of the 2025 course. New course development happens in [`DH-Oz/CorpusAnalysis`](https://github.com/DH-Oz/CorpusAnalysis) (the 2026 Python/Jupyter pivot and beyond).

## Contents

### Original 2025 class (May–June)

- `20250504 corpusmasterclass{1,2,3a,3b}.Rmd` — the four main session lessons.
- `20250516-corpusmasterclass0.Rmd` — prereq / setup document.
- `20250504-corpusmasterclass{1,2,3a,3b}.html` — rendered HTML of each lesson.
- `nietzsche/` — the working corpus (twenty-three Nietzsche texts, plain-text English translations).
- `nietzsche.dic`, `macdvirtue.dic`, `nuke.dic` — custom dictionaries used in the course.
- `nietzsche{WC,virt,virtue}.tiff` — example output figures (word cloud, virtue analysis).
- `year_vs_{anger,anx,sad}.png` — SOTU LIWC emotion-trend plots produced in class 2.
- `todo.md` — a glimpse of the original planning notes.

### Post-class additions (June 2025)

Lessons taught after the original class wrap-up and folded into the archive in 2026.

- `20250616-Corpusmasterclass-4.Rmd` — Day 4 lesson.
- `20250619-Corpus-TFIDF.Rmd` — introducing loops via a PDF → TF-IDF pipeline.
- `20250619-TFIDF-DictionaryBuilder.Rmd` — building a dictionary from TF-IDF output, applying with KWIC.
- `FirstWordcloud.Rmd`, `.html`, `.pdf` — Brian's iterative wordcloud-colouring notebook on the SOTU corpus.
- `curated_terms.dic`, `distinctive_terms.txt`, `terms.txt` — dictionary and TF-IDF term lists produced by the post-class lessons.
- `20250603-BBS-JT-TeachingTheUnknown.pdf` — the conference paper (Ballsun-Stanton & Topping, 2025) that motivated the post-class TF-IDF/KWIC lessons. **CC BY 4.0**, reproduced with author permission.
- `references.bib` — bibliography cited from the post-class lessons and paper.

## Bundled download

A single-zip download of the course materials is available on the [Releases page](https://github.com/DH-Oz/2025-corpus-analysis/releases) — convenient for students who want to grab everything without browsing the repo.

## What is NOT included

**LIWC** (`liwcdict.dic`) is a commercial product and is **not** redistributed here, even though the original 2025 course used it. The lesson source code references `liwcdict.dic` in places — that code will not run end-to-end without a licensed LIWC dictionary supplied separately. Contact the instructors if you have a LIWC licence and want to reproduce the LIWC-based portions of the 2025 course.

**Third-party PDF corpus.** The post-class TF-IDF and DictionaryBuilder lessons (`20250619-*.Rmd`) read from a `pdfs/` directory and from `Tarnowski_phdthesis.pdf`. Those source PDFs are other authors' work and are not redistributed in this archive. To re-run those lessons end-to-end, supply your own small PDF corpus (any folder of `.pdf` files works) and adjust the file paths in the chunks accordingly. The lesson narrative and code are self-contained; only the corpus inputs are missing.

**KWIC excerpts.** The same lessons produce a `kwic_output/` folder of keyword-in-context CSVs derived from the missing third-party PDFs. Because those CSVs would re-distribute short excerpts of the underlying papers, they are also excluded from this archive.

## Licences

- **Lesson content** (Rmd, HTML, prose, custom dictionaries) — [CC BY-NC 4.0](LICENSE-CONTENT.md).
- **Code** (R chunks, Python scratch files) — [MIT](LICENSE-CODE.md).

## Citation

> Alfano, M. & Ballsun-Stanton, B. (2025). *DH Winter School Corpus Analysis Masterclass* (2025 edition). CC BY-NC 4.0. https://github.com/DH-Oz/2025-corpus-analysis

## Contact

Mark Alfano — [contact TBD]
Brian Ballsun-Stanton — brian.ballsun-stanton@mq.edu.au
