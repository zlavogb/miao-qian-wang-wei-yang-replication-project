### WHO checked WHAT, and HOW?

Bianca Zlavog: Forked the target group's repository, checked Q3 and Q4 by exploring the repository's README and LICENSE files, and browsing the data and code file formats used in performing the analysis.

Iacopo Garizio:

James Lee:

Advika Battini: Checked Q1 and Q2 by re-running the workflow based on documentation provided to generate the word document.

### Q1. Do the generated outputs match the ones in the paper in the target group's repo?

Yes, the simulated data is an exact match to the ones generated in the paper. However, there was an error while knitting the paper.Rmd as knitr::include_graphics() was not able to locate some files (figure4-ori.png,figure5-ori.png,table1_re.png,table2_re.png, table3_re.png).

### Q2. Are the differences relevant or not?

There were no differences between the simulated plots by the target group and the rerun of plots.

### Q3. Are used pieces of software and data properly CITED and with suitable LICENSES?

Yes, the authors provide a LICENSE file describing the use terms of the software and data included in the repository. They also clearly describe all software versions and dependencies, and reference the original paper and source of the code and data used.

### Q4. Are open formats (text-based) included?

Yes, the entire analysis is performed using open-source file formats, including the analysis in R and the data files stored as CSVs.

### Q5. Is data and software FAIR?