<br />
<p align="center">
  </a>
  <h1 align="center">A replication of a simulation study on measuring and correcting bias of under-5 mortality estimation in populations affected by HIV/AIDS. </h1>
  <p align="center">

</p>

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Contributors](#contributors)
* [Contents](#contents)
* [Data](#data)
* [Dependencies](#dependencies)

<!-- ABOUT THE PROJECT -->
## Contributors
Sihao Miao [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0003-2242-0906) <br />
Ruian Yang [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0002-0789-2465) <br />
Xiaolu Qian [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0002-8747-1221) <br />
Jiyu Wang [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0002-1283-2934)<br />
David Wei [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0002-4347-5941)<br />

<!-- Contents -->
## Contents
The goal of this project is to complete a professional, publication-worthy replication of a [public health paper](https://bmcpublichealth.biomedcentral.com/articles/10.1186/s12889-019-7780-3).<br />

The paper claims that indirect approaches can introduce bias to under-5 mortality (U5M) estimation in populations affected by HIV/AIDS and their predictive model enables correction of the bias. It is important to us to replicate this paper because its findings can create a substantial impact on public health, especially regarding policies and programs related to the HIV epidemics. <br />

Reference:
Quattrochi, John, ​et al.​ “Measuring and Correcting Bias in Indirect Estimates of under-5 Mortality in Populations Affected by HIV/AIDS: a Simulation Study.” ​BMC Public Health​, vol. 19, no. 1, Dec. 2019, doi:10.1186/s12889-019-7780-3.

<!-- Data -->
## Data
The original data files for performing the individual-level simulation in this paper can be found in this [GitHub repository](https://github.com/jquattro/hiv-childmort-bias) under the data folder provided by the authors.  
 <br />

The README.md file in this repository provides well-documented introduction to the directory structure and scripts. Within the 'R' folder, there are six R script files for conducting simulations and regressions as well as creating tables and figures of the paper. The authors also provided options to turn the parallel computing off to adapt to different computing environments.

We will be able to obtain the same simulation data by running the 001_simulation.R file with provided seed. The generated simulation data will be imported with other input data files provided in the 'results' folder into the 004_regression.R to get a model for the bias and create figures 4 and 5, which are our target figures of this replicating project.
<!-- Dependencies -->
## Dependencies
Here are the packages we need for running the 001_simulation.R file. <br />
─ Packages ──────────────────────────────────── <br />
 package     * version  <br />
 doRedis     * 1.1.1    <br />
 dplyr       * 0.8.0.1  <br />
 forcats     * 0.3.0    <br />
 foreach     * 1.4.4    <br />
 ggplot2     * 3.1.0    <br />
 iterators   * 1.0.10   <br />
 parallel.   * 3.5.2    <br />
 purrr       * 0.3.0    <br />
 readr       * 1.1.1    <br />
 stringr     * 1.4.0    <br />
 tibble      * 2.0.1    <br /> 
 tidyr       * 0.8.2    <br /> 
 tidyverse   * 1.2.1    <br />
```


```
