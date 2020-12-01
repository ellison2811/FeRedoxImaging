# Data processing for quantitative Fe redox imaging

This repository provides the processing code used in *Ellison, E.T., Mayhew, L.E., Miller, H.M., and Templeton, A.S. (2020) [Quantitative microscale Fe redox imaging by multiple energy X-ray fluorescence mapping at the Fe K pre-edge peak](https://doi.org/10.2138/am-2020-7359). _American Mineralogist_, 105, 1812–1829*.
The raw XRF multiple energy map, XANES spectra, and calibration data are included. The code completes all of the processing steps and generates the data figures as well as the supplemental information.

## Reproducibility
This repository reflects the final data analysis presented in the paper and is therefore static.

This package uses [Packrat](https://rstudio.github.io/packrat/) to record the package versions used. For additional platform information, see [sessionInfo.txt](https://github.com/ellison2811/FeRedoxImaging/blob/main/sessionInfo.txt).

  To reproduce the results reported in the paper, [Processing.Rmd](https://github.com/ellison2811/FeRedoxImaging/blob/main/Processing.Rmd) should be run in its entirety. Afterwords, [Supplemental_Figures.Rmd](https://github.com/ellison2811/FeRedoxImaging/blob/main/Supplemental_Figures.Rmd) can be knit in order to generate the supplement.

## License
[GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)
