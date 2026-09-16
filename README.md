# Molecular Orbital Theory — Lecture Slides & Handouts

A collection of lecture slides and detailed handouts covering Molecular Orbital (MO) Theory, designed for computational chemistry education.

## Overview

This repository contains educational materials for a university-level course on Molecular Orbital Theory. The content progresses from foundational concepts to advanced applications in computational chemistry.

### Prerequisites

- General chemistry (atomic structure, chemical bonding)
- Calculus and linear algebra fundamentals
- Basic quantum mechanics

## Structure

```
slides/            # Slide content (markdown format, compatible with reveal.js or pandoc)
  01-introduction.md
  02-lcao-method.md
  ...
handouts/          # Detailed handout material with derivations and examples
  01-introduction-handout.md
  02-lcao-handout.md
  ...
figures/           # MO diagrams, orbital illustrations, and computational outputs
references.bib     # Bibliography for cited works
```

## How to Use

### Slides

Slide files are written in markdown format. They can be rendered using:

- **Pandoc**: `pandoc slides/01-introduction.md -o 01-introduction.pdf`
- **reveal.js**: Convert markdown to HTML slides (see individual slide headers)
- **Direct reading**: Each file includes speaker notes for the lecturer

### Handouts

Handout files provide expanded derivations, worked examples, and supplementary explanations. They are intended as student-facing reference material complementary to the slides.

### Figures

Orbital diagrams and computational output figures go in `figures/`. Use descriptive filenames (e.g., `h2-lcao-diagram.png`).

## License

MIT License — see [LICENSE](LICENSE) file.

## Dependencies

Content drafting is tracked separately in [SVA-70](/SVA/issues/SVA-70).
