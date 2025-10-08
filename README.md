# Valen Li — Resume

This repository contains the source LaTeX files and compiled PDFs for my single-page and multi-page resumes.

## Files
- `singlepage-resume.tex` — LaTeX source for the single-page resume
- `singlepage-resume.pdf` — compiled PDF
- `multipage-resume.tex` — LaTeX source for the multi-page resume
- `multipage-resume.pdf` — compiled PDF

## Build
You can build either resume locally with a LaTeX distribution (e.g., TeX Live or MacTeX):

```bash
pdflatex singlepage-resume.tex
pdflatex multipage-resume.tex
```

If your LaTeX setup requires multiple runs for references, run `pdflatex` twice.

## Notes
- Fonts and margins are tuned for ATS readability and compact layout.
- Links in the header are clickable in the PDFs.

## License
MIT
