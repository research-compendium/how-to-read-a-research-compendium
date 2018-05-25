# How to Read a Research Compendium

"How to Read a Research Compendium" - based on [S. Keshav's "How to Read a Paper"](http://blizzard.cs.uwaterloo.ca/keshav/wiki/index.php/HTRAP).

A PDF is rendered on Travis: [![Build Status](https://travis-ci.org/nuest/how-to-read-a-research-compendium.svg?branch=master)](https://travis-ci.org/nuest/how-to-read-a-research-compendium)

Download it: [https://nuest.github.io/how-to-read-a-research-compendium/how-to-read-a-research-compendium.pdf](https://nuest.github.io/how-to-read-a-research-compendium/how-to-read-a-research-compendium.pdf)

## Render the paper PDF

Rendering the PDF requires `rticles` to be installed from GitHub as the `peerj` article format is not yet on CRAN.

Locally with R:

- Start an R session in the directory of this file
- Run `rmarkdown::render('how-to-read-a-research-compendium.Rmd')`

Locally with a container: See the command used in `.travis.yml`
