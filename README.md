# How to Read a Research Compendium

"How to Read a Research Compendium" is published as a preprint on arXiv:

> Nüst, Daniel, Carl Boettiger, and Ben Marwick. 2018. **"How to read a research compendium."** [arXiv:1806.09525](https://arxiv.org/abs/1806.09525) [cs.GL].

A mobile friendly HTML5 version of the article can be accessed at [https://**ar5iv.org**/html/1806.09525](https://ar5iv.org/html/1806.09525).

The manuscript is based on [S. Keshav's "How to Read a Paper"](http://blizzard.cs.uwaterloo.ca/keshav/wiki/index.php/HTRAP).

This "long-form" guide references numerous resources for technial details on research compendia, but itself is focussed on the full experience of interacting with a research compendium as a reader.
If you want to apply the method presented in the paper, the [**Research Compendium Review Matrix**](https://docs.google.com/spreadsheets/d/18VrkcvTWDyvsldRKfgw2jnhfd5C6xbMwGZNE4ILjXlw/edit?usp=sharing) will be useful.

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

## License

Creative Commons Attribution Share-Alike (CC BY-SA 4.0)
