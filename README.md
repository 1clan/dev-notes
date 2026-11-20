# Dev Notes

Two guides published with GitHub Pages, as browsable documentation and as PDFs, plus their LaTeX sources.

- **The FFmpeg Codebase: A Guided Tour** -- [notes](notes/ffmpeg.html) / [PDF](FFmpegCodebase.pdf)
- **A Practical Path into Low-Level Programming** -- [notes](notes/low-level.html) / [PDF](LowLevelRoadmap.pdf)

## Site

<https://1clan.github.io/dev-notes/>

## Rebuild the PDFs

Both documents are self-contained and compile with plain `pdflatex`:

```sh
pdflatex FFmpegCodebase.tex
pdflatex LowLevelRoadmap.tex
```
