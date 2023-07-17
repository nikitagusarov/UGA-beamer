# UGA beamer tempalte for `pandoc`

This folder includes all the required files for a beamer presentation creation in [University Grenoble Alpes](https://univ-grenoble-alpes.fr) and [Grenoble INP](https://grenoble-inp.fr) styles.
The template may be easily adapted for usage without `pandoc`, in plain LaTeX.

The folder structure is as follows:

```
.
├── alias.sh
├── bibliography
│   └── bibliography.bib
├── example.md
├── example.pdf
├── example.rmd
├── LICENSE
├── logos
│   ├── logo-cnrs.png
│   ├── logo-feg.png
│   ├── logo-gael.png
│   ├── logo-ginp-blanc-orange.png
│   ├── logo-ginp.png
│   ├── logo-gscop.png
│   ├── logo-inrae.png
│   ├── logo-lig.png
│   ├── logo-miai.png
│   ├── logo-uga-blanc-orange.png
│   └── logo-uga.png
├── README.md
└── templates
    ├── packages.tex
    └── ugabeamer.tex
```

The `templates` and `logos` folders should be left as is due to hardcoded paths in the proposed style.
New logos may be added to `logos` folder in a `.png` format, to use them the associated URLs should be added within `templates/ugabeamer.tex` files.
Adding a new logo `logos/logo-new.png` will require an addition of the following line to the template:

```
\def\new{https://url.to-new-webpage.com/}
```