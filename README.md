# SpatialDataAnalysis
Spatial Data Analysis learning materials and project

## Practical
1. Basic Mapping with geopandas & Interactive Mapping with folium \
   `geopandas, pysal, `[`folium (web map)`](https://python-visualization.github.io/folium/#)
   1. reproject
   2. choropleths
   3. [ColorBrewer](http://colorbrewer2.org/)
   4. GeoJSON file
2. Data Handling and Processing
   1. weather data
   2. get data via an API  
   3. distance
3. Spatial and Non-Spatial Joins
   1. raster ([`georasters`](https://pypi.org/project/georasters)/[`GDgeorastersAL`](https://automating-gis-processes.github.io/2016/Lesson7-read-raster.html))
   2. vector (`geopandas`)
   3. [bounding box](https://geopandas.org/geometric_manipulations.html)
4. Point Pattern Analysis (PPA) \
   `PySAL/ `[`pointpats`](https://pointpats.readthedocs.io/en/latest/api.html)
   1. Point distribution analysis (i.e.Centrography and visualization)
      1. Convex Hull (Hull) and Minimum Bounding Rectangle (mbr)
      2. mean_center, weighted_mean_center, manhattan_median, euclidean_median
   2. complete spatial randomness (CSR)
      1. Density Estimates
         <a href="http://scikit-learn.org/stable/tutorial/machine_learning_map/"><img alt="SciKit-Learn Algorithm Map" src="http://scikit-learn.org/stable/_static/ml_map.png"></a>
         ![PySAL Map](http://darribas.org/gds_scipy16/content/figs/pysal.png)
      2. Quadrat Based Statistics
      3. Point Intensity Estimates
   3. Heatmap
   4. Nearest Neighbours
      1. Mean Nearest Neighbor Distance Statistics
      2. K Nearest Neighbors (KNN)
      3. Distance band weights
      4. Kernel weights
   5. NN Classification
      1. bokeh (visualisation)
      2. [Log Loss Functino](http://wiki.fast.ai/index.php/Log_Loss)
   6. [Kernel Density Estimation (KDE)](https://scikit-learn.org/stable/modules/density.html#kernel-density-estimation)
      1. Univariate
      2. Bivariate
      3. Multivariate
5. Buffering & Spatial Interpolation \
   `libpysal.cg.voronoi, scipy.spatial, scipy.interpolate, pykrige`
   1. Voronoi diagram
      1. Trimming by bbox
      2. Voronio weights
      3. [Qhull library](http://www.qhull.org/)
   2. Delaunay Triangulations
      1. conplanar points
   3. Convex Hulls
   4. Buffering
   5. Interpolation
      1. Basic Interpolation
      2. IDW Interpolation
      3. Kriging Interpolation
      4. 2D Kriging Calculation
      5. 2D Kriging Visualization
      6. Variogram
6. Spatial Operation & Multivariate Regression
   1. Spatial relationships and operations
      1. within, distance
      2. intersection, difference, union, cascaded union, contain
      3. dissolve
   2. Aspatial Multivariate Regression
      1. Ordinary Least Squares (OLS)
      2. Regression diagnostics
         1. Omni test (Chi-square, Two-tail probability)
         2. Jarque-Bera
         3. Multicollinearity
         4. Heteroskedasticity test
         5. plots
            * Partial regression plots
            * Influence Plots
            * Leverage-Resid2 Plot
7. Spatial Autocorrelation & Spatial Regression \
   `pysal, libpysal`
   1. Spatial Weights
      1. Contiguity Based Weights (queen, rook, bishop)
      2. Distance Based Weights
      3. Kernel Weights
   2. Spatial Lags
      1. Spatial Similarity
      2. Moran Plot
      3. Global spatial autocorrelation
         * Exploratory Spatial Data Analysis (ESDA)
      4. Local spatial autocorrelation
         * Local Moran's I
   3. Spatial Regression
      1. Spatial Lag model
      2. Spatial Error model
      3. Prediction performance of spatial models
      4. Geographically weighted regression (GWR) Prediction
         * R-square
         * T-test
8. Geodemographics Clustering \
   `sklearn`,`PYSAL`,`sompy`
   1. Data Processing
      1. Tidy up
      2. Normalisation
      3. Standardising
   2. Clustering Realization
      * Ward Clustering
      * DBSCAN Clustering
      * Probabilistic clustering
      * KMeans Clustering
9.  Network Analysis \
   `Netorkx`,`OSMnx`
   1. Networkx Routing
   2. OSMnx Routing
