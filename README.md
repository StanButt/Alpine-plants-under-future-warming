# Alpine plants under future warming
Data repository for Climate refugia and habitat loss for a widespread alpine plant under future warming

## Data availability
Raster script was too large for the GITHUB repository, but to make it still accessible, the download script run in R has been provided, showing how each CHELSA Bioclim layer is downloaded and cropped to the europe shapefile also provided. 
GBIF data has also been provided. This is after the occurence data were cropped and spatially thinned. 

### Packages used
There is script for "1_Packages_and_Functions" which includes all the packages and functions used to create the models. This should be run before any other script to ensure functions and commands work properly. 

## Model Script
The model script can be found in these files, split into sections which cover different components.

### Script order/contents
> Chelsa Climate layers
 - Load/Download Europe shapefile
 - Download and crop current
 - Download and crop hindcast
   - Hindcast URL list in .txt
 - Download and crop future
> GBIF Occurence data
 - Loading in data
 - Thinning data
 - Calculating spatial autocorrelation
 - Spatially partitioning occurence data
> Preliminary Models
 - Calculating Variance Inflation Factor
 - Create and compare multiple preliminary models
> Model Creation
 - Create and visualise current suitability model
 - Create and visualise LGM 21k bp suitability model
 - Create and visualise forecast suitability model
> Other
 - Calculate difference in available suitable habitat
 - Calculate changes in elevation under projected climates
