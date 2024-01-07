# Exploring the effects of built environment factors on metro ridership in Chicago using multiscale geographically weighted regression analysis
The study employs Multiscale Geographically Weighted Regression (MGWR) to analyze spatial variations in metro ridership, taking into account different built environment factors. The research aims to understand the specific scale of metro station catchment areas in Chicago and how these factors contribute to the spatial variation of metro ridership. This study provides valuable insights for urban planners and local authorities, aiding in the development of tailored policies to enhance metro system effectiveness and utilization.
### Data Collection and Cleaning:
Collected data on daily ridership and built environment factors for 116 metro stations across 7 lines in Chicago from various platforms. Data was cleaned using R, ensuring accuracy and consistency in preparation for analysis.

![study area](https://github.com/yikuany/Chicago-L-ridership/assets/150404282/aa3705f9-0e52-42aa-8354-eb80ed52105d)

![variables table](https://github.com/yikuany/Chicago-L-ridership/assets/150404282/14b70360-4d97-4de9-9b12-cb3732bd7bf8)

![Daily Total Ridership](https://github.com/yikuany/Chicago-L-ridership/assets/150404282/7b9fc5f5-1d21-4aed-b7e8-580ec3c432f4)

### Proximity and Service Area Analysis:
Conducted analysis of catchment areas for Chicago metro stations. Utilized ArcGIS toolsets for proximity and service area analysis, focusing on circular buffers, walk-time isochrones, and Thiessen polygons to process data.

![1](https://github.com/yikuany/Chicago-L-ridership/assets/150404282/4ccf727c-f71d-419c-959b-6d7e3ea26067)

![Thi](https://github.com/yikuany/Chicago-L-ridership/assets/150404282/de92be9e-d3c7-4ac6-abf4-80c0f58a8b97)

### Geographically Weighted Regression Analysis:
Statistical tests for normality and multicollinearity of variables were completed using R. Multiscale Geographically Weighted Regression (MGWR) was employed for more precise and localized spatial data modeling compared to traditional methods. This approach identified the scale of catchment areas and built environment factors affecting metro ridership in Chicago through the comparison of 16 MGWR models.

![normality test](https://github.com/yikuany/Chicago-L-ridership/assets/150404282/09e5d4d5-f218-4f57-98fa-ec1e23a6c513)

![multicolinearity tests](https://github.com/yikuany/Chicago-L-ridership/assets/150404282/e859b3a0-57ae-4eeb-a634-252e5896f538)

![Comparison of MGWR models](https://github.com/yikuany/Chicago-L-ridership/assets/150404282/93580669-7b9b-4768-bee1-10ea51c078ca)

![localR residuals](https://github.com/yikuany/Chicago-L-ridership/assets/150404282/b25b94f9-dbfb-46b0-aaaa-e776617fc36e)

### Data-Driven Planning Strategies:
Utilized tmap and ggplot2 libraries in R for data visualization. Studied the specific impacts of factors like land use intensity and road density on ridership, and proposed planning improvement strategies based on these findings.

![bandwidths coefficients](https://github.com/yikuany/Chicago-L-ridership/assets/150404282/7648191b-9a17-4198-8879-d94db6fc4393)

![Coefficients](https://github.com/yikuany/Chicago-L-ridership/assets/150404282/e4d3151e-38ce-461c-8230-9a83ea780ede)
