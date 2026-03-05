# Neuro-symbolic-control

PhD project.
## How to get PDF version
The latest PDF version can be found [here](https://github.com/idzm/Neuro-symbolic-control/releases/latest) (**Assets** section -> main.pdf).



## How to build

Build PDF file:

```sh
latexmk -pdf -outdir=out main.tex
```

Build versioned PDF file:

```sh
latexmk -pdf -outdir=out -jobname="main_" -usepretex="\def\dissertationversion{0.5}" main.tex
```
