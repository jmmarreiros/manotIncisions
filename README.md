
<!-- README.md is generated from README.Rmd. Please edit that file -->

# manotIncisions

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jmmarreiros/manotIncisions/master?urlpath=rstudio)

This repository contains the data and code for our paper:

> Goder-Goldberger, M., Marreiros, J., Paixão, E., Hovers, E. (In
> press). *Incised stone artefacts from the Levantine Middle
> Palaeolithic and human behavioural complexity*. Archaeological and
> Anthropological Sciences

### How to cite

Please cite this compendium as:

> Goder-Goldberger, M., Marreiros, J., Paixão, E., Hovers, E. , (2024).
> *Compendium of R code and data for Incised stone artefacts from the
> Levantine Middle Palaeolithic and human behavioural complexity*.
> Accessed 27 Oct 2024. Online at <https://doi.org/xxx/xxx>

## Contents

The **analysis** directory contains:

- [:file_folder: plots](/analysis/plots): generated plots and images
- [:file_folder: raw_data](/analysis/raw_data): raw data
- [:file_folder: scripts](/analysis/scripts): scripts used for data
  processing and analysis
- [:file_folder: summary_stats](/analysis/summary_stats): results from
  the descriptive analysis

## How to run in your browser or download and run locally

This research compendium has been developed using the statistical
programming language R. To work with the compendium, you will need
installed on your computer the [R
software](https://cloud.r-project.org/) itself and optionally [RStudio
Desktop](https://rstudio.com/products/rstudio/download/).

You can download the compendium as a zip from from this URL:
[master.zip](/archive/master.zip). After unzipping: - open the `.Rproj`
file in RStudio - run `devtools::install()` to ensure you have the
packages this analysis depends on (also listed in the
[DESCRIPTION](/DESCRIPTION) file). - finally, open
`analysis/paper/paper.Rmd` and knit to produce the `paper.docx`, or run
`rmarkdown::render("analysis/paper/paper.Rmd")` in the R console

### Licenses

**Text and figures :**
[CC-BY-4.0](http://creativecommons.org/licenses/by/4.0/)

**Code :** See the [DESCRIPTION](DESCRIPTION) file

**Data :** [CC-0](http://creativecommons.org/publicdomain/zero/1.0/)
attribution requested in reuse

### Contributions

We welcome contributions from everyone. Before you get started, please
see our [contributor guidelines](CONTRIBUTING.md). Please note that this
project is released with a [Contributor Code of Conduct](CONDUCT.md). By
participating in this project you agree to abide by its terms.

For any questions related to the code or research please contact the
corresponding authors:

- Mae Goder-Goldberger, <maego@post.bgu.ac.il>
- João Marreiros, <joao.marreiros@leiza.de>
