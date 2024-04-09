# Sentinel-2-Grid-Overlay
Within this repository, we provide the corresponding files to our contribution "SENTINEL-2 TILING SCHEME GRID-OVERLAY FOR EFFICIENT I/O-OPERATIONS
BASED ON SPHERICAL VORONOI POLYGONS AND LOCAL OPTIMIZATION" at IGARSS 2024.
Please have a look at the publication for further information!

The repository is organized as follows:
- data
    - shapefile (download all and use shp)
        - *sentinel-s2-l1c_ScipyVoronoiPolygons.shp* - shapefile for the grid-overlay with the names of the polygons as index 
    - numpy
        - *sentinel-s2-l1c_ScipyVoronoiPolygons.npy* - numpy array with Voronoi polygons of the grid-overlay
        - *sentinel-s2-l1c_ScipyVoronoiPolygons_Bboxes.npy* - numpy array with the bounding boxes of the Voronoi polygons of the grid-overlay
        - *sentinel-s2-l1c_TileCenters.npy* - numpy array with the centroids of the Voronoi polygons in LonLat
        - *sentinel-s2-l1c_TileEPSGs.npy* - numpy array with the epsg codes of the Voronoi polygons
        - *sentinel-s2-l1c_TileNames.npy* - numpy array with the names of the Voronoi polygons