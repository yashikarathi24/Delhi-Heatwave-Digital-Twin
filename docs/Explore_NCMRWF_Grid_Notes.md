# NCMRWF Grid Exploration

## Objective
Understand the spatial structure and coverage of the NCMRWF weather data before integrating it with high-resolution explanatory datasets.

## Tasks Performed

- Explored the latitude and longitude coordinates of the NCMRWF dataset.
- Calculated the spacing between adjacent grid points.
- Determined that each weather grid cell represents approximately **13 km × 12 km** over Delhi.
- Visualized the complete NCMRWF weather grid.
- Constructed weather cell polygons from the grid coordinates.
- Obtained the administrative boundary of the National Capital Territory (NCT) of Delhi using OpenStreetMap (OSMnx).
- Overlayed the weather grid on the Delhi boundary.
- Performed spatial analysis to identify weather cells covering Delhi.

## Key Findings

- Total weather cells in the downloaded dataset: **136**
- Weather cells intersecting Delhi: **19**
- Weather observations are available at a coarse spatial resolution, making them suitable for regional weather representation but insufficient for neighbourhood-level analysis.

## Technologies Used

- Python
- Google Colab
- NumPy
- Matplotlib
- GeoPandas
- Shapely
- OSMnx
- OpenStreetMap
- xarray
- NetCDF

## Conclusion

The exploration provided a clear understanding of the NCMRWF spatial grid and its coverage over Delhi. This analysis will guide the integration of higher-resolution datasets such as NDVI, Land Use/Land Cover, Population Density, and Building Density in the subsequent stages of the project.