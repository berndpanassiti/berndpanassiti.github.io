# 





### R package: HostSwitch

> The R package ''HostSwitch'' simulates host switches by a consumer.

## Background
Symbiosis describes the interaction between to different biological organisms. In a biological system with a parasite (or consumer) and a host (or resource) we may encounter (stochastic) events where the parasite switches to a new host. This so called 'Host switching' was first simulated by {{< cite "Araujo2015" >}} to explore the host switch of a consumer under different settings. This simulation model was the basis for the Stockholm paradigm, a theoretical framework explaining the evolution of new biological associations.

## The R package
Based on the simulation model by {{< cite "Araujo2015" >}}, we developed a R-package, called 'HostSwitch'. This package contains all functionalities to simulate host switching by a consumer, and additionally:
* let you choose between different scenarios
* offers enhanced visualisation options
* provides you the possibility to test between two different hypotheses and much more...

A recent paper by {{< cite "Trivellone2021" >}} provides an in-depth description of the ''HostSwitch'' package.

The R-package is available on CRAN: [https://cran.r-project.org/web/packages/HostSwitch/index.html](https://cran.r-project.org/web/packages/HostSwitch/index.html)

To install the package from CRAN and load the package:
```{r}
install.packages("HostSwitch")
library(HostSwitch)
```


The R-package is also available on GitHub: [https://github.com/berndpanassiti/HostSwitch](https://github.com/berndpanassiti/HostSwitch)

To install the package from GitHub repository:
```{r}
devtools::install_github(repo = "berndpanassiti/HostSwitch",build_vignettes = TRUE)
```




### Bibliography
<!-- The bibliography will display works from path/to/bib.json -->
{{< bibliography cited >}}
