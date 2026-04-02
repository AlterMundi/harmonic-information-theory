# Harmonic Information Theory

This repository contains the editorial source of the book *Harmonic Information Theory: Foundations*. Its center of gravity is the LaTeX edition from which the bibliographic PDF is composed, revised, and published. It should not be read as the general repository of the broader research program, nor as a container for every experimental branch associated with Phideus, Beacon, or related work. Its function is narrower and clearer: to preserve the book as an identifiable editorial work, together with the materials directly tied to its composition and publication.

The work is authored by **Mariano Fernández Méndez** and **Nicolás Echániz**. **Compilation and final writing** correspond to **Mariano Fernández Méndez**. The book is developed and published within the institutional framework of **Asociación Civil AlterMundi** and is accompanied by an explicitly credited research and development team.

## Editorial Status

The publication architecture of *Harmonic Information Theory* is distributed across coordinated formats with different functions:

- The **PDF** is the official bibliographic edition of the book. Its ISBN is currently **in process**.
- The **Markdown manuscript** is an official complementary open version of the same work, structured for segmented reading, indexing, and computational navigation.
- This **repository** is the open editorial source of the book. It does **not** carry an ISBN as an independent bibliographic product.

This distinction matters. The work is one. Its supports are several. They should not be collapsed into one another.

## What This Repository Contains

The repository is organized around a small editorial core:

- `LaTeX/` — the compositional source of the book, including `main.tex`, chapter files, bibliography, and frontmatter.
- `Harmonic_Information_Theory_Foundations.md` — the complementary Markdown manuscript of the same work.
- `Publicacion/` — the current editorial, legal, licensing, and publication policy documents used as source of truth for implementation.
- `ARQUITECTURA_LIBRO.md` — the book architecture and structural blueprint.
- `bibliografia_HIT.md` — the broader bibliographic substrate assembled around the book.
- `BITACORA.md` — the editorial and epistemic log used to stabilize prose, distinctions, and narrative decisions across the manuscript.

## What This Repository Is Not

This repository is not the general repository of the wider research program. It is not the canonical home of all Phideus or Beacon code, datasets, runs, or experimental operations. Related research repositories may exist and may be linked from official publication channels, but they should be understood as related projects, not as parts of this editorial repository itself.

## Building the PDF

The LaTeX edition is built from `LaTeX/main.tex`. The standard compilation sequence is:

```bash
cd LaTeX
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

This produces the current working PDF at `LaTeX/main.pdf`.

## License and Attribution

Unless otherwise indicated, the contents of this repository are distributed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

<https://creativecommons.org/licenses/by/4.0/>

This license permits copying, redistribution, adaptation, transformation, and reuse, including for commercial purposes, provided that appropriate attribution is given, the license is linked, changes are indicated, and no endorsement by the authors or Asociación Civil AlterMundi is implied without express authorization.

Suggested attribution:

Fernández Méndez, Mariano, and Nicolás Echániz. *Harmonic Information Theory*. Asociación Civil AlterMundi, 2026. Official PDF bibliographic edition, ISBN in process. License: CC BY 4.0. Official source: [OFFICIAL URL].

## Official Source and Contact

- **Official source:** [OFFICIAL URL]
- **Contact:** [CONTACT EMAIL]

Until those public coordinates are finalized, the placeholders above should be preserved exactly as placeholders rather than replaced with local or machine-specific paths.
