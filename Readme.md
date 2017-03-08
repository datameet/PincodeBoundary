Postal Boundary Data
====

This Repository contains the spatial data of Pincode Boundaries as available on [NIC's Post-office site]( http://postoffice.umd.nic.in:8080/nicutility/)



====

**Note on the Formats**
This data is in GeoJSON format. The advantage of this is that Github directly shows this on the Map

In the GIS industry, Shapefiles are the defacto Standard Format, but it also sufferes from several issues. This is why I have decided not to keep Shapefiles in this Repo. Those who need shapefiles, can always convert these formats to Shapefile, using something like GDAL. This can be achieved by something as simple as the following command:

`ogr2ogr output.shp input.geojson`

If you need to view them in a Desktop GIS, I'll recommend QGis

====

**License**

The dataset shared under [Creative Commons Attribution-ShareAlike 2.5 India](http://creativecommons.org/licenses/by-sa/2.5/in/) license.