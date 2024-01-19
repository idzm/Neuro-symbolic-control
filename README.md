# Neuro-semantic-control

PhD project.

## How to build

Build PDF-file:

```sh
latexmk -pdf -outdir=out main.tex
```

Build versioned PDF-file:

```sh
latexmk -pdf -outdir=out -jobname="main_" -usepretex="\def\dissertationversion{0.5}" main.tex
```
