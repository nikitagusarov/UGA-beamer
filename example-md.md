---
title: UGA Beamer Seminar Template
subtitle: Lorem ipsum dolor sit amet
author: John Doe$^a$ and Jane Doe$^b$
institute: |
    $^a$ GAEL, University Grenoble Alpes \par
    $^b$ G-SCOP, University Grenoble Alpes \par
credits: With funding from AWESOME Corp.
email: john.doe@univ-grenoble-alpes.fr
date: 01/09/2000
aspectratio: 169 # aspect ration of the page
class: seminar # `seminar` or `conference`
toplogo: uga # `uga` or `ginp`
logos: 
    - uga
    - ginp
    - gael
    - gscop
    # More options are available:
    # - miai
    # - feg
    # - lig
    # - cnrs
    # - inrae
bibliography: bibliography/bibliography.bib
nocite: "@misc2"
# Other available parameters
# For the exact usage please see the templates/ugabeamer.tex file
# fontsize: 12
# fontfamily:
# fonttheme: 
# mathfont:
# papersize: 
# background-image: figures/some_image.png
# geometry:
# margins:
#     left:
#     right:
# padding: # defaults to 0cm
# tables:
# multirow:
# graphics:
# lof: # list of figures
# lot: # list of tables
# toc-title: 
# csl-refs:  # use CSL references
# include-before:
# include-after:
# Parameters that might be used with .Rmd or .Qmd documents
# For more parameters see Rmarkdown or Quarto documentation
## Rmarkdown part
# output:
#   beamer_presentation:
#     template: templates/ugabeamer.tex
#     keep_tex: false
#     slide_level: 2
#     toc: true
#     includes:
#       in-header: templates/packages.tex
## Quarto part
# format:
#   beamer:
#     template: templates/ugabeamer.tex
#     slide-level: 2
#     toc: true
#     includes:
#       in-header: templates/packages.tex
---



# Introduction

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. 
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.



# Part 1

* Lorem ipsum dolor sit amet, 
* consectetur adipiscing elit, 
* sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 

## Subsection 1.1

Citation @book1 :

> Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

## Subsection 1.2

```
# Duis aute 
irure = dolor in reprehenderit + voluptate
```

* Excepteur sint occaecat cupidatat non proident, 
    - sunt in culpa [@book2]
    - qui officia deserunt mollit [@misc1]



# Part 2

## Table

The table is presented in table (@tbl:table).

Table: some table {#tbl:table}

| Some table | Contents                |
| ---------- | ----------------------- |
| Here       | Contents for this table |



# Bibliography

## Bibliography