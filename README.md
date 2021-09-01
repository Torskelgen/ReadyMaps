The "kommuner_simp_##.geojson" files are simplified versions of the municipality and county datasets provided by GeoNorge for illustration purposes.

Simplified means in this case that the number of vertices/points in the municipality geometries has been drastically reduced. 
The main benefit of this is file size and drawing speed. For instance, the file size of the 2017 version is reduced from 45 MB to 1.2 MB.
The simplification was done with the ms_simplify() function in the R package rmapshaper.

License: Creative Commons 0
