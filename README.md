# Harmonic Information Theory

This repository contains the LaTeX source of the book *Harmonic Information Theory: Foundations*. It is the open editorial source from which the official PDF bibliographic edition is composed, revised, and published. Its function is precise: not to absorb the wider research program into a single technical container, but to preserve the book as an identifiable editorial work and to keep its compositional source available in a stable and open form.

The work is authored by **Mariano Fernández Méndez** and **Nicolás Echániz**. **Compilation and final writing** correspond to **Mariano Fernández Méndez**. The book was developed and published within the institutional framework of **Asociación Civil AlterMundi**.

## What This Repository Contains

- `LaTeX/main.tex` — the main compositional source of the book.
- `LaTeX/chapters/` — chapter files (introduction, 16 chapters, appendices, legal page, writing process note).
- `LaTeX/references.bib` — the full bibliography in BibTeX format.

## Building the PDF

```bash
cd LaTeX
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

This produces the working PDF at `LaTeX/main.pdf`.

## Editorial Status

- The **PDF** is the official bibliographic edition of the book. Its ISBN is **978-631-91761-0-0**.
- The PDF currently exported from this source and fixed on **2026-04-17** is the **first digital edition** of the book and should be treated as the closed bibliographic artifact of that edition.
- This **repository** is the open editorial source. It does **not** carry an ISBN as an independent bibliographic product.

The distinction matters because the work is one while its supports are not identical. The bibliographic edition, the editorial source, and the broader public circulation of the book belong to the same publication architecture, but they do not play the same role.

## License

Unless otherwise indicated, the contents of this repository are distributed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

<https://creativecommons.org/licenses/by/4.0/>

This license permits copying, redistribution, adaptation, transformation, and reuse, including for commercial purposes, provided that appropriate attribution is given, the license is linked, changes are indicated, and no endorsement by the authors or Asociación Civil AlterMundi is implied without express authorization.

**Suggested attribution:**

Fernández Méndez, Mariano, and Nicolás Echániz. *Harmonic Information Theory: Foundations*. José de la Quintana, Córdoba, Argentina: AlterMundi, 2026. ISBN 978-631-91761-0-0. License: CC BY 4.0. Official source: https://hit.altermundi.net.

## Official Source and Contact

- **Official source:** https://hit.altermundi.net
- **Contact:** editorial@altermundi.net
