[![Build Status](https://travis-ci.org/monocongo/climate_indices.svg?master)](https://travis-ci.org/monocongo)
[![Coverage Status](https://coveralls.io/repos/github/monocongo/climate_indices/badge.svg?branch=master)](https://coveralls.io/github/monocongo/climate_indices?branch=master)
[![CodeFactor](https://www.codefactor.io/repository/github/monocongo/climate_indices/badge/master)](https://www.codefactor.io/repository/github/monocongo/climate_indices/overview/master)
[![License](https://img.shields.io/badge/License-BSD%203--Clause-green.svg)](https://opensource.org/licenses/BSD-3-Clause)
<!--
[![Dependency Status](https://gemnasium.com/badges/github.com/monocongo/climate_indices.svg)](https://gemnasium.com/github.com/monocongo/climate_indices)
[![Codeship Status for monocongo/climate_indices](https://app.codeship.com/projects/0d711e30-ca42-0135-871a-72c36ec6d502/status?branch=master)](https://app.codeship.com/projects/261762)
[![Documentation](https://readthedocs.org/projects/indices-python/badge/?version=latest)](http://indices-python.readthedocs.io/en/latest/?badge=latest)
-->
# Climate Indices in Python

This project contains Python implementations of various climate index algorithms which provide 
a geographical and temporal picture of the severity of precipitation and temperature anomalies
useful for climate monitoring and research.

The following indices are provided:

-  [SPI](https://climatedataguide.ucar.edu/climate-data/standardized-precipitation-index-spi),
   Standardized Precipitation Index, utilizing both gamma and Pearson Type III distributions
-  [SPEI](https://www.researchgate.net/publication/252361460_The_Standardized_Precipitation-Evapotranspiration_Index_SPEI_a_multiscalar_drought_index),
   Standardized Precipitation Evapotranspiration Index, utilizing both gamma and Pearson Type III distributions
-  [PET](https://www.ncdc.noaa.gov/monitoring-references/dyk/potential-evapotranspiration),
   Potential Evapotranspiration, utilizing either [Thornthwaite](http://dx.doi.org/10.2307/21073)
   or [Hargreaves](http://dx.doi.org/10.13031/2013.26773) equations 
-  [PDSI](http://www.droughtmanagement.info/palmer-drought-severity-index-pdsi/),
   Palmer Drought Severity Index
-  [scPDSI](http://www.droughtmanagement.info/self-calibrated-palmer-drought-severity-index-sc-pdsi/),
   Self-calibrated Palmer Drought Severity Index
-  [PHDI](http://www.droughtmanagement.info/palmer-hydrological-drought-index-phdi/),
   Palmer Hydrological Drought Index
-  [Z-Index](http://www.droughtmanagement.info/palmer-z-index/),
   Palmer moisture anomaly index (Z-index)
-  [PMDI](https://climate.ncsu.edu/climate/climdiv), Palmer Modified
   Drought Index
-  [PNP](http://www.droughtmanagement.info/percent-of-normal-precipitation/),
   Percentage of Normal Precipitation

This Python implementation of the above climate index algorithms is being developed 
with the following goals in mind:

-  to provide an open source software package to compute a suite of
   climate indices commonly used for climate monitoring, with well
   documented code that is faithful to the relevant literature and
   which produces scientifically verifiable results
-  to provide the climate monitoring and research community a central, open 
   location for participation and collaboration
-  to facilitate standardization and consensus on best-of-breed
   climate index algorithms and compliant implementations
-  to provide transparency into the operational code used for climate
   monitoring activities at NCEI/NOAA, and consequent reproducibility 
   of published datasets computed from this package
-  to incorporate modern software engineering principles and programming 
   best practices


This is a developmental/forked version of code that is originally developed and 
maintained by NIDIS/NCEI/NOAA. The official release version is available at 
[drought.gov](drought.gov).

* [__Documentation__](https://indices-python.readthedocs.io/en/latest/)
* [__License__](LICENSE)
* [__Disclaimer__](DISCLAIMER)
