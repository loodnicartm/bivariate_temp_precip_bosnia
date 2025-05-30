# bivariate_temp_precip_bosnia
This R script performs a bivariate spatial analysis of long-term temperature and precipitation trends across Bosnia and Herzegovina. By combining Theil-Sen slope estimations for both variables, it produces a bivariate choropleth map that highlights areas experiencing significant climate change patterns.

-Key Features:
Load and preprocess raster stacks of monthly/annual temperature and precipitation.

Compute Theil-Sen trend slopes for each pixel over time.

Classify and quantile-scale both variables to produce a bivariate representation.

Generate a custom bivariate color palette for intuitive visual interpretation.

Export a final bivariate trend map showing joint climate trends spatially.

-Technologies & Libraries Used:
raster, terra, rgdal – for geospatial data processing

zyp, trend, Kendall – for non-parametric trend estimation

ggplot2, cowplot, grid, RColorBrewer – for high-quality mapping

-Applications:
Climate change analysis at the regional scale

Environmental planning and policy support

Identification of hotspots of drying/warming or cooling/wetting

Integration with agricultural or hydrological impact assessments

![bosnia_bivariate_2d__](https://github.com/user-attachments/assets/a256d9e2-1eab-4385-a0db-1b0208336385)

Adopted after: Miloš Popović

