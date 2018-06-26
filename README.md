# How to Read a Research Compendium

"How to Read a Research Compendium" is published as a preprint on arXiv:

> Nüst, Daniel, Carl Boettiger, and Ben Marwick. 2018. **"How to read a research compendium."** [arXiv:1806.09525](https://arxiv.org/abs/1806.09525) [cs.GL].

The manuscript is based on [S. Keshav's "How to Read a Paper"](http://blizzard.cs.uwaterloo.ca/keshav/wiki/index.php/HTRAP).

This "long-form" guide references numerous resources for technial details on research compendia, but itself is focussed on the full experience of interacting with a research compendium as a reader.

## Read draft

A PDF is rendered on Travis: [![Build Status](https://travis-ci.org/nuest/how-to-read-a-research-compendium.svg?branch=master)](https://travis-ci.org/nuest/how-to-read-a-research-compendium)

Download it: [https://nuest.github.io/how-to-read-a-research-compendium/how-to-read-a-research-compendium.pdf](https://nuest.github.io/how-to-read-a-research-compendium/how-to-read-a-research-compendium.pdf)

## Render the paper PDF locally

Rendering the PDF requires `rticles` to be installed from GitHub as the `peerj` article format is not yet on CRAN.

Locally with R:

- Start an R session in the directory of this file
- Run `rmarkdown::render('how-to-read-a-research-compendium.Rmd')`

Locally with a container: See the command used in `.travis.yml`.

## Contributors

- [Daniel Nüst](https://github.com/nuest/)
- [Ben Marwick](https://github.com/benmarwick/)
- [Carl Boettiger](https://github.com/cboettig/)
