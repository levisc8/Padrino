
<!-- README.md is generated from README.Rmd. Please edit that file -->
Padrino
=======

Padrino a package for interacting with the demography data base of the same name. It consists wrappers to an SQL data base that itself houses a suite of all known, published integral projection models. It is the brain child of Roberto Salguero-Gomez and others. Currently, it does not exist, but we hope to change in that in the coming months. With that in mind, please be patient as we build it out.

### Installation and contribution

You can install Padrino from github with:

``` r
# install.packages("devtools")
devtools::install_github("levisc8/Padrino")
```

Alternatively, if you'd like tontribute to development, please fork the repo, make your updates, and submit a pull request. We welcome programmers of any level who wish to make meaningful contributions to the project.

### Notes

-   The data base itself does not currently exist. However, this does not necessarily preclude us from developing its functionality! Given the challenges of ensuring that anyone can fully reproduce a model which may have a variety of idiosyncracies (i.e. the authors used some obscenely obscure package to create their growth function), it is not too early to start figuring out programatic solutions to these problems. Examples include:
    -   Bayesian models to estimate model parameters may become more common in the not distant future. Given the ubiquity of *Stan* and *JAGS*, how do we implement these?
