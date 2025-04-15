OOI-on-BCO-DMO
==============================
[![License:MIT](https://img.shields.io/badge/License-MIT-lightgray.svg?style=flt-square)](https://opensource.org/licenses/MIT)
<!-- [![conda-forge](https://img.shields.io/conda/dn/conda-forge/ooi-on-bco-dmo?label=conda-forge)](https://anaconda.org/conda-forge/ooi-on-bco-dmo) -->

## Overview
The NSF Ocean Observatories Initiative (OOI) provides Discrete CTD and Water Sampling Cruise Data for each Array as a dataset in the Biological and Chemical Oceanography Data Management Office (BCO-DMO). This notebook plots Oxygen, Salinity, Nitrate, and Chlorophyll data from the Global Irminger Sea Array from 2014-2023 ([doi:10.26008/1912/bco-dmo.911407.1](https://www.bco-dmo.org/dataset/911407)) Repository with Jupyter Notebooks to request data and create visualizations with the NSF Ocean Observatories Initiative (OOI) Discrete CTD and Water Sampling Cruise Data in the Biological and Chemical Oceanography Data Management Office (BCO-DMO).


## Background
The hydrographic sampling performed by The NSF Ocean Observatories Initiative (OOI) as part of each Array turn represents a significant collection of valuable physical, chemical, and biological information. In addition to the CTD, collected hydrographic data include discrete oxygen, salinity, nutrient (nitrate, nitrite, silicate, phosphate, ammonium), chlorophyll, and carbon system measurements. These data serve several important functions. First, they are necessary for the calibration and evaluation of the moored instrumentation at each Array. Furthermore, the annual (Global/Cabled Array) or biannual (Coastal Pioneer/Endurance) collection of data at the same locations provides a unique timeseries of a large set of water properties following established community standards and methods, independent of its association with the OOI moorings.

The Biological and Chemical Oceanography - Data Management Office (BCO-DMO) specializes in making biological and chemical oceanographic researchers findable, accessible, interoperable, and reusable (FAIR) to the science community. These FAIR data principles are achieved through BCO-DMO’s services, which includ: public data access; ontological metadata standardization; data archive and DOI creation; and standardized version control practices.



The analysis of collected water samples for the parameters listed above are performed by a number of outside labs on behalf oOOISN. Consequently, the water sampling data for a given cruise is distributed among a number of different files. The Discrete Sampling Summary integrates the related CTD, metadata, and discrete water sample data into a single file. Additionally, it synthesizes qualitative and quantitative information about the quality of a measurement into data quality flags for each associated parameter which follow WOCE-standard
 The final product is the Discrete Sampling Summary spreadsheet which contains the metadata, CTD data, and discrete water sample data into a single spreadsheet with data quality flag.

O).---
></p>

Note: If making use of Jupyter Notebooks or the [OOI JupyterHub](https://jupyter.oceanobservatories.org/) for data exploration and analysis as demonstrated in this repo, following installation and activating the environment, you will need to execute the following code to be able to select the environment as your no\tebook's k

e```l:
"""python -m ipykernel install --user --name myenv --display-name "Python (my```)" """
