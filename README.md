# Marine Aquaculture Suitability

Exploration of suitability of the West Coast of the United States for marine aquaculture. Marine aquaculture is a growing industry and an important consideration in the global food supply. Analyzing the West Coasts Exclusive Economic zones considering sea surface temperature and water depth for different species will allow for species level analysis of economic potential. 

## Visualizations
There will be two main visualizations produced in the `.Rmd` file. These visualizations will show the suitability of the main Exclusive Economic Areas on the West Coast by total area and percentage of suitability for two species, oysters and shrimp.


## Highlights
-   combining vector/raster data
-   resampling raster data
-   masking raster data
-   map algebra

## Data
The data associated with this project was accessed from this [link](https://drive.google.com/u/0/uc?id=1u-iwnPDbe6ZK7wSFVMI-PpCKaRQ3RVmg&export=download).

Data for this project was also accessed from the [US Census Bureau](https://www.census.gov/geographies/mapping-files/time-series/geo/cartographic-boundary.html) at the 1:500,000 National scale.

Store data locally and add `data` folder to the `.gitignore`.

```{r}
marine-aquaculture
│   README.md
│   Rmd/Proj files    
│
└───data
    │   wc_regions_clean.shp
    │   depth.tif
    │   average_annual_sst_2008.tif
    │   average_annual_sst_2009.tif        
    │   average_annual_sst_2010.tif        
    │   average_annual_sst_2011.tif
    │   average_annual_sst_2012.tif     
```
