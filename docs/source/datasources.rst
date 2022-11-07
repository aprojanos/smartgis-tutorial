Datasources
======

To create maps, you must first add data sources. These can be files, database connections or services from external map servers (WMS, tile servers).

File datasources
----------------

Supported vector formats 

* ESRI ShapeFile
* ESRi Geopdatabase
* Mapinfo TAB
* Mapinfo MIF
* Autocad DXF
* GeoJSON
* KML

Supported raster formats

* TIFF
* JPEG

.. Tip:: Folders with raster files can be uploaded via FTP service and imported as a datasource

.. Note:: explain 'add to application's database', 'add to project'

.. Tip:: Check datasource as Basemap

Organize files into folders
---------------------------

Application database
--------------------

The application stores spatial data in its own PostGIS database as layers. 
Layers can be divided into two groups: they can be edited or just used to create maps. Editing layers on the map is done with 2D/3D digitization tools. See section: :ref:`Layer editor <layer_editor>`
The form editor can be used to specify how the attribute table is filled. See section: :ref:`Field editor <field_editor>`


External databases
------------------

Supported databases

* MySQL
* PostgreSQL - PostGIS
* MS SQL Spatial
* Oracle Spatial


WMS connections
---------------

External map services
---------------------

Supported services

* Bing maps
* XYZ compatible tile services 

