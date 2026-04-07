Explaining South Asian Monsoon Rainfall Seasonality Using a Metric of Plume Buoyancy
------------

[![Published Paper](https://img.shields.io/badge/Published%20Paper-10.1029%2F2025GL115546-1f6feb?style=for-the-badge&logo=readthedocs&logoColor=white)](https://doi.org/10.1029/2025GL115546)
[![Archived Code](https://img.shields.io/badge/Archived%20Code-10.5281%2Fzenodo.19005467-1f6feb?style=for-the-badge&logo=github&logoColor=white)](https://doi.org/10.5281/zenodo.19005467)

This repository contains the code for the analyses in Ferretti et al. (2025, *Geophysical Research Letters*). The exact version used in the paper is archived on Zenodo. For questions or feedback, contact Savannah Ferretti (savannah.ferretti@uci.edu).

**Authors & Affiliations:**  
Savannah L. Ferretti<sup>1</sup>, Michael S. Pritchard<sup>1</sup>, Fiaz Ahmed<sup>2</sup>, Liran Peng<sup>1</sup>, & Jane W. Baldwin<sup>1,3</sup>  
<sup>1</sup>Department of Earth System Science, University of California Irvine, Irvine, CA, United States  
<sup>2</sup>Department of Atmospheric and Oceanic Sciences, University of California Los Angeles, Los Angeles, CA, United States  
<sup>3</sup>Lamont-Doherty Earth Observatory, Palisades, NY, United States  

**Abstract**: Localized tropical rainfall changes commonly occur on 500-1,000 km scales under various climate forcings, but understanding their causality remains challenging. One helpful process-oriented diagnostic (POD) decomposes the effects of undilute buoyancy and lower free-tropospheric moisture through a precipitation-buoyancy relationship, but its applicability at subregional scales is uncertain. We examine month-to-month rainfall changes in five South Asian monsoon subregions. The POD accurately characterizes the precipitation-buoyancy relationship across all subregions and successfully predicts the sign of rainfall changes in four out of five subregions. However, the POD's ability to predict rainfall change magnitudes and identify causal mechanisms varies, providing confident explanations in only two subregions, where lower free-tropospheric moisture emerges as the dominant driver of change. While these findings demonstrate the POD's utility in specific contexts, they also reveal limitations. We caution against using the POD as a standalone tool at these scales for predicting rainfall changes or decomposing their drivers.

Project Organization
------------
```
├── LICENSE.md         <- License for code
├── README.md          <- Top-level information on this code base/manuscript
├── data/
│   ├── raw/           <- Original ERA5, IMERG V06, and GPCP data
│   ├── interim/       <- Intermediate processed data
│   └── processed/     <- Analysis-ready data
├── figs/              <- Manuscript figures
├── notebooks/         <- Jupyter notebooks for data processing, analysis, and visualization 
└── environment.yml    <- File for reproducing the analysis environment
```

Acknowledgements
-------

The analysis for this work was performed on PSC's [Bridges-2](https://www.psc.edu/resources/bridges-2/) and NERSC's [Perlmutter](https://docs.nersc.gov/systems/perlmutter/architecture/). This research was primarily funded by [LEAP NSF-STC](https://leap.columbia.edu/), with additional support from the US DOE's [ASCR](https://www.energy.gov/science/ascr/advanced-scientific-computing-research) and [RGMA](https://eesm.science.energy.gov/program-area/regional-global-model-analysis) Programs, the [Exascale Computing Project](https://www.exascaleproject.org/), NSF's [AGS](https://www.nsf.gov/geo/ags), and NASA's [ECIP-ES](https://science.nasa.gov/earth-science/early-career-opportunities/#h-early-career-investigator-program-in-earth-science). Additionally, we thank Quentin Nicolas, William R. Boos, and Nana Liu for their valuable input in shaping the early stages of this work.
