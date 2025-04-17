OOI-on-BCO-DMO
==============================
[![License:MIT](https://img.shields.io/badge/License-MIT-lightgray.svg?style=flt-square)](https://opensource.org/licenses/MIT)

## Overview
The NSF Ocean Observatories Initiative (OOI) provides Discrete CTD and Water Sampling Cruise Data for each Array as a dataset in the Biological and Chemical Oceanography Data Management Office (BCO-DThis repository includes Jupyter Notebooks to request data and create visualizations with OOI Discrete CTD and Water Sampling Cruise Data in BCO-DMO, in particular to plot Oxygen, Salinity, and Nitrate data from the Global Irminger Sea Array from 2014-2023 2023 ([doi:10.26008/1912/bco-dmo.911407.1](https://www.bco-dmo.org/dataset/91DMO).


## Background
The hydrographic sampling performed by [The NSF Ocean Observatories Initiative (OOI)](https://oceanobservatories.org/) as part of each Array turn represents a significant collection of valuable physical, chemical, and biological information. In addition to the CTD, collected hydrographic data include discrete oxygen, salinity, nutrient (nitrate, nitrite, silicate, phosphate, ammonium), chlorophyll, and carbon system measurements. These data serve several important functions. First, they are necessary for the calibration and evaluation of the moored instrumentation at each Array. Furthermore, the annual (Global/Cabled Array) or biannual (Coastal Pioneer/Endurance) collection of data at the same locations provides a unique timeseries of a large set of water properties following established community standards and methods, independent of its association with the OOI moorings.

The [Biological and Chemical Oceanography - Data Management Office (BCO-DMO)](https://www.bco-dmo.org/) specializes in making biological and chemical oceanographic researchers findable, accessible, interoperable, and reusable (FAIR) to the science community. These FAIR data principles are achieved through BCO-DMO’s services, which includ: public data access; ontological metadata standardization; data archive and DOI creation; and standardized version control practices.

The analysis of collected water samples for the parameters listed above are performed by a number of outside labf s obehalf oOOISN. Consequently, the water sampling data for a given cruise is distributed among a number of different files. The Discrete Sampling Summary integrates the related CTD, metadata, and discrete water sample data into a single file. Additionally, it synthesizes qualitative and quantitative information about the quality of a measurement into data quality flags for each associated parameter modified which follow WOCE-standards.
 
The final product is the Discrete Sampling Summary spreadsheet which contains the metadata, CTD data, and discrete water sample data into a single spreadsheet with data qual## Use
This repository includes an ```environment.yml``` file to allow the user to download the repository, configure the environment, and run the example notebooks as presented. The following steps will allow you to get accessing, downloading, and plotting data: 

```
# download the ooi-on-bco-dmo repo
mkdir -p ~/Documents/GitHub
cd ~/Documents/GitHub
git clone git@github.com:WHOIGit/ooi-on-bco-dmo.git
cd ooi-on-bco-dmo

# configure the ooi-on-bco-dmo python environment
conda env create -f environment.yml
conda init # might be required for windows users if environment is not active
conda activate ooi-on-bco-dmo

# you can check the active environment by running
conda env listi```
ty flag.

---


Note: If making use of Jupyter Notebooks or the [OOI JupyterHub](https://jupyter.oceanobservatories.org/) for data exploration and analysis as demonstrated in this repo, following installation and activating the environment, you will need to execute the following code to be able to select the environment as your notebook's kernel:

``` python -m ipykernel install --user --name myenv --display-name "Python

---
## Additional Documentation
Further documentation may be found in the **cruise_data** folder on the [OOI Raw Data Archive](https://rawdata.oceanobservatories.org/files/cruise_data/), which includes the original cast and sampling logs, as well as the individual results spreadsheets from the labs which conduct the analyses on behalf of OOI. 

Additionally, datasets with calibrated CTD casts using methods adapted from the GO-SHIP and NOAA/PMEL for the Irminger Sea by Leah McRaven are reference on the [OOI Community Datasets](https://oceanobservatories.org/community-datasets/) page. (ooi-on-bco-dmo)" ```
