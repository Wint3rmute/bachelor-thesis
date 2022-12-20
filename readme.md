# Bachelor Thesis

Yadda yadda autonomous drones go wrrr and there's a nice dashboard to see what they're up to :)

## Building

```bash
pdflatex -f -interaction=nonstopmode Dyplom.tex
```

This thesis is using a [latex template](http://tomasz.kubik.staff.iiar.pwr.wroc.pl/) created by Tomasz Kubik. Kudos!

## Dependencies

Installing `texlive-core` and `texlive-fontsextra` should be enough to build the thesis.
If you're having problems, here's a list of all packages I have installed:

```bash
$ pacman -Q | grep texlive                                
  texlive-bibtexextra
  texlive-bin
  texlive-core
  texlive-fontsextra
  texlive-formatsextra
  texlive-games
  texlive-latexextra
  texlive-music
  texlive-pictures
  texlive-pstricks
  texlive-publishers
  texlive-science
```

