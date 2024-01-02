# Exploring the effects of built environment factors on metro ridership in Chicago using multiscale geographically weighted regression analysis
The study employs Multiscale Geographically Weighted Regression (MGWR) to analyze spatial variations in metro ridership, taking into account different built environment factors. The research aims to understand the specific scale of metro station catchment areas in Chicago and how these factors contribute to the spatial variation of metro ridership. This study provides valuable insights for urban planners and local authorities, aiding in the development of tailored policies to enhance metro system effectiveness and utilization.
### Data Collection and Cleaning:
Collected data on daily ridership and built environment factors for 116 metro stations across 7 lines in Chicago from various platforms. Data was cleaned using R, ensuring accuracy and consistency in preparation for analysis.
### Proximity and Service Area Analysis:
Conducted analysis of catchment areas for Chicago metro stations. Utilized ArcGIS toolsets for proximity and service area analysis, focusing on circular buffers, walk-time isochrones, and Thiessen polygons to process data.
### Geographically Weighted Regression Analysis:
Statistical tests for normality and multicollinearity of variables were completed using R. Multiscale Geographically Weighted Regression (MGWR) was employed for more precise and localized spatial data modeling compared to traditional methods. This approach identified the scale of catchment areas and built environment factors affecting metro ridership in Chicago through comparions of 16 MGWR models.
### Data-Driven Planning Strategies:
Utilized tmap and ggplot2 libraries in R for data visualization. Studied the specific impacts of factors like land use intensity and road density on ridership, and proposed planning improvement strategies based on these findings.
