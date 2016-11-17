# habs
**Demo Sphinx project for CW WCRN**

**Description:**

| The HABS nowcast and forecast model uses satellite and modeled environmental data to forecast the probability of a harmful algal bloom event along the west coast the the US. This documentation covers the coding for the CoastWatch portion of the project, which covers the following steps:
  * downloading NASA MODIS L2 data;
  * extracting chlorophyll a, rf488 nm, and rf555 nm bands;
  * gridding the data binning them into daily composite;
  * compiling 180 days of data for each band and filling in missing data with DINEOF;
  * downsampling the data to the ROMS model resolution and writing to a netCDF4 file.

**Disclaimers:**

This script is provided "as is" without warranty of any kind.

The United States Department of Commerce (DOC) GitHub project code is provided on an ‘as is’ basis and the user assumes responsibility for its use. DOC has relinquished control of the information and no longer has responsibility to protect the integrity, confidentiality, or availability of the information. Any claims against the Department of Commerce stemming from the use of its GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC or the United States Government.
