# UC Berkeley — Fall 2026 Course Notes

LaTeX lecture notes for my Fall 2026 courses at UC Berkeley, written up from my handwritten notes during the semester. New lectures are added as the term goes on, so the links below always point to the latest version.

**William Nguyen** · Mathematics, UC Berkeley

## Notes

| Course | Topics | Notes | Source |
| --- | --- | --- | --- |
| **MATH 142** — Elementary Algebraic Topology | Point-set topology, topological groups, the fundamental group, simplicial complexes, Van Kampen's theorem | [PDF](MATH%20142%20Notes/MATh%20142%20Notes.pdf) | [.tex](https://github.com/nontrivialwill/UC-Berkeley-Fall-2026/tree/main/MATH%20142%20Notes) |
| **MATH 202A** — Introduction to Topology and Analysis | Measure theory, Lebesgue integration, convergence theorems, product measures, differentiation, bounded variation | [PDF](MATH%20202A%20Notes/MATH%20202A%20Notes.pdf) | [.tex](https://github.com/nontrivialwill/UC-Berkeley-Fall-2026/tree/main/MATH%20202A%20Notes) |
| **STAT 210A** — Theoretical Statistics | Sufficiency, exponential families, Rao–Blackwell and Cramér–Rao, Bayes and minimax estimation, hypothesis testing | [PDF](STAT%20210A%20Notes/STAT%20210A%20Notes.pdf) | [.tex](https://github.com/nontrivialwill/UC-Berkeley-Fall-2026/tree/main/STAT%20210A%20Notes) |
| **STAT C205A** — Probability Theory | Measure-theoretic probability, integration and L<sup>p</sup> spaces, independence, zero-one laws, modes of convergence | [PDF](STAT%20C205A%20Notes/STAT%20C205A%20Notes.pdf) · [Midterm 1 cheat sheet](STAT%20C205A%20Notes/Midterm1CheatSheet.pdf) | [.tex](https://github.com/nontrivialwill/UC-Berkeley-Fall-2026/tree/main/STAT%20C205A%20Notes) |

## Repository layout

Each course folder contains:

- `<Course> Notes.tex` / `.pdf` — the full set of notes, compiled as a single book
- `LectureN.tex` — one file per lecture, pulled into the main file with `\include`
- `Images/` — figures, named `LectureNFigM.png`
- `Editor.tex` — a scratch file for drafting the current lecture

To build a course's notes yourself, compile `<Course> Notes.tex` with `pdflatex` from inside that course's folder.

## Disclaimer

These are my personal notes, not official course materials, and they may contain mistakes. If you spot an error, feel free to [open an issue](https://github.com/nontrivialwill/UC-Berkeley-Fall-2026/issues).
