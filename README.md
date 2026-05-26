# CIE A-Level Economics book

Open LaTeX source and a compiled PDF for an economics textbook-style manuscript.

**Repository:** [github.com/Chessing234/economics-book](https://github.com/Chessing234/economics-book)

## Download

- **Latest PDF:** [Releases](https://github.com/Chessing234/economics-book/releases) — each release attaches `ecobook.pdf`.
- **Source:** `ecobook.tex` in this repository.

## Build from source

You need a LaTeX distribution (e.g. TeX Live, MacTeX, MiKTeX). From this directory:

```bash
latexmk -pdf ecobook.tex
```

If the build asks for `cover_illustration.png`, add that file next to `ecobook.tex` or adjust the path in the source.

## Corrections and feedback

**Please use [GitHub Issues](https://github.com/Chessing234/economics-book/issues)** to report typos, unclear explanations, broken references, or factual corrections. One issue per topic (or per chapter section) makes updates easier to track. Pull requests are welcome if you already have a LaTeX fix.
