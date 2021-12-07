# Evaluating the effectiveness of three spatial cluster analysis methods on Palaeolithic site location distributions in Galicia, NW Iberian Peninsula: source code and data
This repository contains data and code to enable reproducibility of the paper "Evaluating the effectiveness of three spatial cluster analysis methods on Palaeolithic site location distributions in Galicia, NW Iberian Peninsula"

## Repository structure
/csv/*.csv ... contains CSV files with the data of the sites and the random points.

/figures/ ... folder with the figures used in the paper in PDF format.

/output/ ... folder with the output files in PDF format.

/shp/ ... folder with the layers of the sites, the random points and the study area in vector format.

/percolation/ ... folder for percolation analysis.

/xls/ ... contains XLS files with the data of the sites and the random points.

Diaz_and_Fabregas_21.Rmd ... Rmarkdown file to reproduce the analysis.

Diaz_and_Fabregas_21.html ... html file to reproduce the analysis.

## R Packages used
[cluster](https://cran.r-project.org/web/packages/cluster/index.html) - Cluster Analysis.

[dbscan](https://cran.r-project.org/web/packages/dbscan/index.html) - Various density-based algorithms methods.

[factoextra](https://cran.r-project.org/web/packages/factoextra/index.html) - Extract and visualize the results of Multivariate Data Analyses

[fpc](https://cran.r-project.org/web/packages/fpc/index.html) - Various methods for clustering and cluster validation.

[ggplot2](https://cran.r-project.org/web/packages/ggplot2/index.html) - Package for creating graphics.

[GISTools](https://cran.r-project.org/web/packages/GISTools/index.html) - Mapping and spatial data manipulation tools.

[gridExtra](https://cran.r-project.org/web/packages/gridExtra/index.html) - User-level functions to work with "grid" graphics.

[igraph](https://cran.r-project.org/web/packages/igraph/index.html) - Package for generating graphs and network analysis.

[maptools](https://cran.r-project.org/web/packages/maptools/index.html) - Set of tools for manipulating geographic data.

[NbClust](https://cran.r-project.org/web/packages/NbClust/index.html) - Package for determining the best number of clusters in a data set.

[percopackage](https://github.com/SCSchmidt/percopackage/) - Package for calculating percolation analysis.

[plyr](https://cran.r-project.org/web/packages/plyr/index.html) - Set of tools that solves problems relates with applying or combining data.

[readxl](https://cran.r-project.org/web/packages/readxl/index.html) - Package for read excel files.

[rgdal](https://cran.r-project.org/web/packages/rgdal/index.html) - Provides bindings to the “GDAL” and “PROJ” library.

[rgeos](https://cran.r-project.org/web/packages/rgeos/index.html) - Package for topology operations on geometries.

[sp](https://cran.r-project.org/web/packages/sp/index.html) - Classes and methods for spatial data.

[spatstat](https://cran.r-project.org/web/packages/spatstat/index.html) - Toolbox for analysing Spatial Point Patterns.

[tidyverse](https://cran.r-project.org/web/packages/tidyverse/index.html) - Data representations and API design.

### References about the packages

Auguie, B., Antonov, A., 2017. gridExtra: Miscellaneous Functions for “Grid” Graphics.

Baddeley, A., Turner, R., Rubak, E., 2020. spatstat: Spatial Point Pattern Analysis, Model-Fitting, Simulation, Tests.

Bivand, R., Keitt, T., Rowlingson, B., Pebesma, E., Sumner, M., Hijmans, R., Rouault, E., Warmerdam, F., Ooms, J., Rundel, C., 2020a. rgdal: Bindings for the “Geospatial” Data Abstraction Library.

Bivand, R., Lewin-Koh, N., Pebesma, E., Archer, E., Baddeley, A., Bearman, N., Bibiko, H.-J., Brey, S., Callahan, J., Carrillo, G., Dray, S., Forrest, D., Friendly, M., Giraudoux, P., Golicher, D., Gómez Rubio, V., Hausmann, P., Hufthammer, K.O., Jagger, T., Johnson, K., Lewis, M., Luque, S., MacQueen, D., Niccolai, A., Pebesma, E., Prepiñán Lamigueiro, O., Plunkett, E., Rubak, E., Short, T., Snow, G., Stabler, B., Stokely, M., Turner, R., 2020b. maptools: Tools for Handling Spatial Objects.

Bivand, R., Rundel, C., Pebesma, E., Stuetz, R., Hufthammer, K.O., Giraudoux, P., Davis, M., Santilli, S., 2020c. rgeos: Interface to Geometry Engine - Open Source ('GEOS’).

Brunsdon, C., Chen, H., 2014. GISTools: Some further GIS capabilities for R.

Charrad, M., Ghazzali, N., Boiteau, V., Niknafs, A., 2015. NbClust: Determining the Best Number of Clusters in a Data Set.

Csardi, G., Nepusz, T., 2006. [The igraph software package for complex network research](http://www.interjournal.org/manuscript_abstract.php?361100992). InterJournal Complex Sy, 1695.

Hahsler, M., Piekenbrock, M., Arya, S., Mount, D., 2019. dbscan: Density Based Clustering of Applications with Noise (DBSCAN) and Related Algorithms.

Hennig, C., 2020. fpc: Flexible Procedures for Clustering.

Kassambara, A., Mundt, F., 2020. factoextra: Extract and Visualize the Results of Multivariate Data Analyses.

Maddison, M.S., Schmidt, S.C., 2020. [Percolation Analysis – Archaeological Applications at Widely Different Spatial Scales](https://journal.caa-international.org/article/10.5334/jcaa.54/). J. Comput. Appl. Archaeol. 3, 269–287. doi:10.17605/OSF.IO/7EXTC.

Maechler, M., Rousseeuw, P., Struyf, A., Hubert, M., Hornik, K., 2019. cluster: Cluster Analysis Basics and Extension.

Pebesma, E., Bivand, R., Rowlingson, B., Gomez-Rubio, V., Hijmans, R., Sumner, M., MacQueen, D., Lemon, J., Lindgren, F., O’Brien, J., O’Rourke, J., 2020. sp: Classes and Methods for Spatial Data.

Wickham, H., 2020. plyr: Tools for Splitting, Applying and Combining Data.

Wickham, H., Averick, M., Bryan, J., Chang, W., D’Agostino McGowan, L., François, R., Grolemund, G., Hayes, A., Henry, L., Hester, J., Kuhn, M., Lin Pedersen, T., Miller, E., Milton Bache, S., Müller, K., Ooms, J., Robinson, D., Piage Seidel, D., Spinu, V., Takahashi, K., Vaughan, D., Wilke, C., Woo, K., Yutani, H., 2019a. [Welcome to the tidyverse](https://joss.theoj.org/papers/10.21105/joss.01686). J. Open Source Softw. 4, 1686. doi:10.21105/joss.01686

Wickham, H., Bryan, J., Kalicinski, M., Valery, K., Leitienne, C., Colbert, B., Hoerl, D., Miller, E., 2019b. readxl: Read Excel Files.

Wickham, H., Chang, W., Henry, L., Pedersen, T.L., Takahashi, K., Wilke, C., Woo, K., Yutani, H., Dunnington, D., 2020. ggplot2: Create Elegant Data Visualisations Using the Grammar of Graphics.

## Source code and data reference
Mikel Díaz-Rodríguez<a href="https://orcid.org/0000-0002-2703-1507">
<img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="14" height="14" />
</a> & Ramón Fábregas-Valcarce<a href="https://orcid.org/0000-0002-7940-6884">
<img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="14" height="14" />
</a>. (2021, April 30). Evaluating the effectiveness of three spatial cluster analysis methods on Palaeolithic site location distributions in Galicia, NW Iberian Peninsula: source code and data (Version v1.0). Zenodo. http://doi.org/10.5281/zenodo.4729680

[![DOI](https://zenodo.org/badge/360846133.svg)](https://zenodo.org/badge/latestdoi/360846133)

[Link in Zenodo](https://zenodo.org/badge/latestdoi/360846133)

## License
CC-BY 4.0
