# Asymptotic Methods

Course notes, reference material, and homework for Asymptotic Methods.

- `guy_notes.tex` and `guy_notes.pdf`: edited transcription of Guy's handwritten notes, with source-page references, marked corrections, and reconstructed steps.
- `homework_solutions.tex` and `homework_solutions.pdf`: homework questions and worked solutions.
- The remaining PDFs contain handwritten source notes, assignment questions, and reference material.

## Building the notes

Use a LaTeX installation with `pdflatex`. Run each command twice to resolve the contents and references:

```sh
pdflatex guy_notes.tex
pdflatex guy_notes.tex
pdflatex homework_solutions.tex
pdflatex homework_solutions.tex
```

Source PDFs and compiled study PDFs are versioned. LaTeX build intermediates, generated page previews, and temporary files are ignored.

New notes can be incorporated into the existing LaTeX edition while preserving consistent notation and marking inferred steps and substantive corrections.
