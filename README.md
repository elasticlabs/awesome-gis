# Awesome GIS 
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/elasticlabs/awesome-gis)](https://github.com/elasticlabs/awesome-gis/stargazers)
![GitHub contributors](https://img.shields.io/github/contributors/elasticlabs/awesome-gis)
![GitHub last commit](https://img.shields.io/github/last-commit/elasticlabs/awesome-gis)
[![GitHub license](https://img.shields.io/github/license/elasticlabs/awesome-gis)](https://github.com/elasticlabs/awesome-gis/blob/master/LICENSE)

> A collection of awesome resources on Geospatial data and software, including cartographic / geoanalysis / developer tools, data, online tutorials & courses, and more.

**Please contribute to make this guide better!** Please follow the [Contributing Guidelines](https://github.com/elasticlabs/awesome-gis/blob/master/ContributingGuidelines.md). 
Inspired by [Awesome Python](https://github.com/vinta/awesome-python) and [Awesome earth Observation Code](https://github.com/acgeospatial/awesome-earthobservation-code)

<p>
  <img src="https://raw.githubusercontent.com/elasticlabs/awesome-gis/main/header.png" alt="Awesome GIS" width="300px">
</p>

**Table Of Contents:**
  - [Learning resources and platforms](#learning-resources-and-platforms)
    - [Data formats](#data-formats)
    - [MOOC](#mooc)
  - [Data and Utilities ](#data-and-utilities)
  - [Geographic Information System Software](#geographic-information-system-software)
  - [Web Map Servers](#web-map-servers)
  - [Spatial Databases](#spatial-databases)
  - [Javascript frontend frameworks and librairies](#javascript-frontend-frameworks-and-librairies)
    - [Map display libraries](#map-display-libraries)
    - [Visual data analysis](#visual-data-analysis)
  - [Language based Geospatial Libraries](#language-based-geospatial-libraries)
    - [C++](#c++)
    - [Python](#python)
  - [Open Forums and communities](#open-forums-and-communities)
  - [Awesome-Awesomeness](#awesome-awesomeness)

----

## Learning resources and platforms
| ▲ [Top](#awesome-gis) |
| --- |
### Data formats
- [Vector Formats](http://www.gdal.org/ogr_formats.html) -  GDAL vector formats: ESRI Shapefile, ESRI ArcSDE, ESRI FileGDB, MapInfo, GML, KML, PostGIS, Oracle Spatial, ...
- [Raster Formats](http://www.gdal.org/formats_list.html) - GDAL raster formats: GeoTIFF, Erdas Imagine, ECW, MrSID, JPEG2000, DTED, NITF, ...
### MOOC
- [Coursera's GIS Specialization](https://www.coursera.org/specializations/gis) - Including `Fundamentals of GIS`, `GIS Data Formats, Design and Quality`, `Geospatial and Environmental Analysis`, `Imagery, Automation, and Applications` and `Capstone: Geospatial Analysis`.
- [Geospatial Intelligence & the Geospatial Revolution](https://www.coursera.org/course/geoint)
- [Maps and the Geospatial Revolution](https://www.coursera.org/course/maps)

## Data and Utilities
| ▲ [Top](#awesome-gis) |
| --- |
**Utilities**
 - [BBox finder](http://bboxfinder.com/) - Select an area and get BBox information in vairous projections and formats.
 - [epsg.io](http://epsg.io/) - Coordinate systems worldwide
 - [mapskin](http://mapsk.in/) - a collection of scalable vector icons for geospatial.
 - [GeoTrellis](https://github.com/locationtech/geotrellis) - A geographic data processing engine for high performance applications that uses Spark to work with raster data. 

**Data download services**
  - [ASTER GDEM](https://gdemdl.aster.jspacesystems.or.jp/) or [From NASA](https://search.earthdata.nasa.gov/search/) - fantastic worldwide DEM jointly built in partnership between the NASA and Japan METI.
  - [BBBike OSM Extracts](https://extract.bbbike.org/) - Extract specific areas of OSM data in common formats (Shapefile, PBF, OSM XML, GeoJSON, etc.)
  - [NASA earthe data](https://search.earthdata.nasa.gov/search/) - A very HUGE directory of awesome geographic data. You must know by advance what you're looking at.
  - [GEBCO Gridded Bathymetry Data](https://www.gebco.net/data_and_products/gridded_bathymetry_data/) - The GEBCO_2020 grid is a global terrain model for ocean and land at 15 arc-second intervals. 
  - [Geo Maps](https://github.com/simonepri/geo-maps) - High Quality GeoJSON maps programmatically generated.
  - [Geofabrik](http://download.geofabrik.de/) - This server has data extracts from the OpenStreetMap project which are normally updated every day. Select your continent and then your country of interest from the list, and enjoy hight quality localized extracts for your apps!
  - [Global cities Shapefile data](http://download.bbbike.org/osm/bbbike/)
  - [Metro extracts](https://mapzen.com/data/metro-extracts/) - City-sized portions of OpenStreetMap
  - [Natural Earth](https://www.naturalearthdata.com/) - A public domain dataset available at 1:10m, 1:50m, and 1:110 million scales. Featuring tightly integrated vector and raster data, with Natural Earth you can make a variety of visually pleasing, well-crafted maps with cartography or GIS software.
  - [OpenDEM](https://opendem.info/index.html) - Open Digital Elevation Model (OpenDEM) The Portal for sharing the 3rd Dimension.
  - [OpenDataSoft](https://data.opendatasoft.com/explore/) - More than 20000 curated high quality data sets library available for download.
  - [Open Street Map](https://www.openstreetmap.org/) - A map of the world, created by people like you and free to use under an open license.
  - [OpenFlights: Airport and airline data](http://openflights.org/data.html) - Awesome FOSS airports and airlines database.
  - [Open Weather Map](https://openweathermap.org/api/weathermaps) - OpenWeatherMap provides many kinds of weather maps including Precipitation, Clouds, Pressure, Temperature, Wind. You can connect them to mobile and web apps.
  - [Overpass API](https://wiki.openstreetmap.org/wiki/Overpass_API) - The Overpass API (formerly known as OSM Server Side Scripting, or OSM3S before 2011) is a read-only API that serves up custom selected parts of the OSM map data. 
  - [Sentinel Hub](https://apps.sentinel-hub.com/eo-browser/) - A complete archive of Sentinel-1, Sentinel-2, Sentinel-3, Sentinel-5P, ESA’s archive of Landsat 5, 7 and 8, global coverage of Landsat 8, Envisat Meris, MODIS, Proba-V and GIBS products in one place.

## Geographic Information System Software
| ▲ [Top](#awesome-gis) |
| --- |
**Free and Open Source (FOSS)**
  - [QGIS](http://qgis.org/en/site/) ![Python](resources/icon/python.png) :star2: - A free and open source GIS.
  - [GeoDa](http://geodacenter.github.io/) ![C++](resources/icon/cplusplus.png) - A free and open source software tool that serves as an introduction to spatial data analysis.
  - [GISInternals](http://www.gisinternals.com/) ![C++](resources/icon/cplusplus.png) - Povides daily build packages and software development kits for the GDAL and MapServer
  - [GRASS GIS](https://grass.osgeo.org/) ![C++](resources/icon/cplusplus.png) - A free and open source GIS software suite used for geospatial data management and analysis, image processing, graphics and maps production, spatial modeling, and visualization.
  - [gvSIG](http://www.gvsig.com/en) ![C++](resources/icon/cplusplus.png) - A powerful, user-friendly, interoperable GIS.
  - [uDig](http://udig.refractions.net/) ![Java](resources/icon/java.png) - An open source (EPL and BSD) desktop application framework, built with Eclipse Rich Client (RCP) technology.

**Commercial**
  - [ArcGIS Desktop](https://www.esri.com/en-us/arcgis/products/arcgis-desktop/overview) :star2: - Extendable desktop suite to manage, visualize and analyze GIS data in 2D and 3D, including image processing. Includes ArcGIS Pro, ArcMap, ArcCatalog, and ArcGIS Online.
  - [Global Mapper](http://www.bluemarblegeo.com/products/global-mapper.php) :star2: - An easy-to-use, robust, and genuinely affordable GIS application that combines a wide array of spatial data processing tools with access to an unparalleled variety of data formats.

## Web Map Servers
| ▲ [Top](#awesome-gis) |
| --- |
**Free and Open Source (FOSS)**
  - [MapServer](http://www.mapserver.org/) ![C++](resources/icon/cplusplus.png) - Publishing spatial data and interactive mapping applications to the web
  - [QGIS Server](https://docs.qgis.org/1.8/en/docs/user_manual/working_with_ogc/ogc_server_support.html) ![Python](resources/icon/python.png) - a FastCGI/CGI application written in C++ that works together with a webserver.
  - [deegree](http://www.deegree.org/) ![Java](resources/icon/java.png) - An open source software for spatial data infrastructures and the geospatial web
  - [Google Earth Enterprise](https://github.com/google/earthenterprise) ![C++](resources/icon/cplusplus.png) - the open source release of Google Earth Enterprise, a geospatial application which provides the ability to build and host custom 3D globes and 2D maps.
  - [GeoNode](http://geonode.org/) ![Java](resources/icon/java.png) ![Javascript](resources/icon/javascript.png) - Open Source Geospatial Content Management System.
  - [GeoServer](http://geoserver.org/) ![Java](resources/icon/java.png) - An open source server for sharing geospatial data
  - [GeoWebCache](https://www.geowebcache.org/) ![Java](resources/icon/java.png) - A java web application used to cache map tiles coming from a variety of sources such as OGC WMS in order to accelerate and optimize map image delivery.
  - [Mapnik](http://mapnik.org/) ![C++](resources/icon/cplusplus.png) - An open source mapping toolkit for desktop-based and server-based map rendering 
  - [OpenMapTiles](https://openmaptiles.org/) ![C++](resources/icon/cplusplus.png) ![Docker](resources/icon/docker.png) - Set of open-source tools for self-hosting of OpenStreetMap maps in more than 50 languages. It provides both raster as well as vector tiles, WMS and WMTS services for GIS programs, support for JavaScript viewers and mobile SDK.
    
**Commercial**
  - [ArcGIS Server](http://server.arcgis.com/) :star2: - A GIS server for enterprise application.
  - [NextGIS Web](http://nextgis.com/nextgis-web) - An open source framework for storage, visualization and permissions management of all kinds of geospatial data.

**Cloud Services**
  - [Mapbox](https://www.mapbox.com/) :star2: - Helping you design your own map and presenting your data
  - [ArcGIS Online](https://developers.arcgis.com/) :star2: - Thousands of datasets and dozens of tools to manipulate, analyze and present data.
  - [Cartodb](http://cartodb.com/) - The easiest way to map and analyze your location data
  - [GIS Cloud](http://www.giscloud.com/) - A next generation platform for apps that manage location information
  - [NextGIS](http://nextgis.com/) - A cloud geospatial service that allows you to create web GIS right in the browser

## Spatial Databases
- [PostGIS](http://postgis.net/) based on [PostgreSQL](http://www.postgresql.org/) ![postgreSQL](resources/icon/postgresql.png) :star2: - Most advanced open source database
- [Spatialite](https://www.gaia-gis.it/fossil/libspatialite/index) based on [SQLite](https://www.sqlite.org/) - Lightweight SQL library to support fully spatially capability
- [MBtiles](https://github.com/mapbox/mbtiles-spec) - A specification for storing tiled map data in SQLite databases
- [GeoMesa](http://www.geomesa.org/) ![Python](resources/icon/python.png) - An open-source, distributed, spatio-temporal database built on a number of distributed cloud data storage systems, including Accumulo, HBase, Cassandra, and Kafka.

## Javascript frontend frameworks and librairies
| ▲ [Top](#awesome-gis) |
| --- |
### Map display libraries 
- [Leaflet](http://leafletjs.com/) ![Javascript](resources/icon/javascript.png) - Open source javaScript library for mobile-friendly interactive maps
- [Mapbox GL JS](https://www.mapbox.com/mapbox-gl-js/api/) ![Javascript](resources/icon/javascript.png) - A JavaScript & WebGL library that renders interactive maps from vector tiles and the Mapbox GL Style Specification
- [OpenLayers](http://openlayers.org/) ![Javascript](resources/icon/javascript.png) - Open source JavaScript map viewing library
- [ArcGIS API for JavaScript](https://developers.arcgis.com/javascript/) ![Javascript](resources/icon/javascript.png) - Creating high-performing apps and smarter visualizations supported by ESRI
- [Tangram](https://github.com/tangrams/tangram) ![Javascript](resources/icon/javascript.png) - A JavaScript library for rendering 2D & 3D maps live in a web browser with WebGL
- [Mapstore 2](https://mapstore.geo-solutions.it/mapstore/#/) ![Javascript](resources/icon/javascript.png) - Awesome modern GIS WebApp built on ReactJS and using Openlayers, Leaflet.
- [mViewer](https://github.com/geobretagne/mviewer) ![Javascript](resources/icon/javascript.png) - Thematic Web GIS viewer based on OpenLayers 6.3.1 and Bootstrap 3.3.6
- [mViewer Studio](https://github.com/geobretagne/mviewerstudio/) ![Javascript](resources/icon/javascript.png) - mViewer confirguration generator
- [mapbox-gl-native](https://github.com/mapbox/mapbox-gl-native) ![Javascript](resources/icon/javascript.png) - A library for embedding interactive, customizable vector maps into native applications on multiple platforms
- [Mapnik](http://mapnik.org/) ![C++](resources/icon/cplusplus.png) - C++ library for map rendering.
- [deck.gl](https://github.com/uber/deck.gl) ![Javascript](resources/icon/javascript.png) - WebGL2 powered geospatial visualization layers.
- [GeoExt](https://geoext.github.io/geoext3/) ![Javascript](resources/icon/javascript.png) - Open Source and enables building desktop-like GIS applications through the web. It is a JavaScript framework that combines the GIS functionality of OpenLayers with the user interface of the ExtJS library provided by Sencha.
- [Windshaft](https://github.com/CartoDB/Windshaft) ![NodeJS](resources/icon/nodejs.png) - A Node.js map tile library for PostGIS and torque.js, with CartoCSS styling.

**3D Specialized**
  - [three.js](http://threejs.org/) ![Javascript](resources/icon/javascript.png) - A JavaScript 3D library which makes WebGL simpler
  - [CesiumJS](https://cesiumjs.org/) ![Javascript](resources/icon/javascript.png)  - An open source JavaScript library for world-class 3D globes and maps
  - [three-geo](https://github.com/w3reality/three-geo) ![Javascript](resources/icon/javascript.png) - Is a three.js based geographic visualization library
  - [iTowns](http://www.itowns-project.org/) ![Javascript](resources/icon/javascript.png) - A Three.js-based framework written in Javascript/WebGL for visualizing 3D geospatial data. It can connect to WMS/WMTS/TMS servers including elevation data and load many different data formats (3dTiles, gpx, KML and much much more).

### Visual data analysis
| ▲ [Top](#awesome-gis) |
| --- |
- [D3.js](https://d3js.org/) ![Javascript](resources/icon/javascript.png) - A JavaScript library for manipulating documents based on data
- [Echarts](http://echarts.baidu.com/) ![Javascript](resources/icon/javascript.png) - A user-friendly data visualisation library supported by Baidu
- [turf.js](http://turfjs.org/) ![Javascript](resources/icon/javascript.png) - Advanced geospatial analysis for browsers and node supported by Mapbox
- [Polymaps](http://polymaps.org/) ![Javascript](resources/icon/javascript.png) - A JavaScript library for image- and vector-tiled maps using SVG
- [jVectorMap](http://jvectormap.com/) ![Javascript](resources/icon/javascript.png) - A vector-based, cross-browser and cross-platform component for interactive geography-related data visualization on the web. [Github Link](https://github.com/bjornd/jvectormap)
- [CMV](https://cmv.io/) ![NodeJS](resources/icon/nodejs.png) - The Configurable Map Viewer (CMV) is an open source mapping framework that works with ESRI JavaScript API, ArcGIS Server, ArcGIS Online, and more.
- [SuperMap iClient JavaScript](http://iclient.supermap.io) - Cloud GIS web client development platform supported by SuperMap.
- [d3-geomap](https://d3-geomap.github.io/) ![Javascript](resources/icon/javascript.png) - A library for creating geographical maps based on D3.js.
- [Baremaps](https://www.baremaps.com/)![NodeJS](resources/icon/nodejs.png)  - An open source pipeline for producing Mapbox vector tiles from OpenStreetMap with Postgis and Java.
- [Hootenanny](https://github.com/ngageoint/hootenanny) ![NodeJS](resources/icon/nodejs.png) - Hootenanny conflates multiple maps into a single seamless map.
- [kepler.gl](https://uber.github.io/kepler.gl/#/) ![Javascript](resources/icon/javascript.png) - kepler.gl is a data-agnostic, high-performance web-based application for visual exploration of large-scale geolocation data sets.
- [mapshaper](https://github.com/mbloch/mapshaper) ![Javascript](resources/icon/javascript.png) - Tools for editing Shapefile, GeoJSON, TopoJSON and CSV files.

## Language based Geospatial Libraries
| ▲ [Top](#awesome-gis) |
| --- |
### C++
- [GEOS](https://trac.osgeo.org/geos/) ![C++](resources/icon/cplusplus.png) - GEOS (Geometry Engine - Open Source) is a C++ port of the Java Topology Suite (JTS).
- [GDAL](http://www.gdal.org/) ![C++](resources/icon/cplusplus.png) - Geospatial Data Abstraction Library (GDAL) is a computer library that serve as a translator library for raster and vector geospatial data formats.
- [tippecanoe](https://github.com/mapbox/tippecanoe) ![C++](resources/icon/cplusplus.png) - Build vector tilesets from large collections of GeoJSON features.
- [gdalcubes](https://github.com/appelmar/gdalcubes) ![C++](resources/icon/cplusplus.png) - gdalcubes is a library to represent collections of Earth Observation (EO) images as on demand data cubes (or multidimensional arrays).
- [PDAL](https://pdal.io/) ![C++](resources/icon/cplusplus.png) - PDAL is Point Data Abstraction Library. GDAL for point cloud data.

### Python
- [Shapely](https://github.com/Toblerity/Shapely) ![Python](resources/icon/python.png) - A library for manipulation and analysis of geometric objects in the Cartesian plane.
- [Rasterio](https://github.com/mapbox/rasterio) ![Python](resources/icon/python.png) - A library for reads and writes geospatial raster data)
- [GeoPandas](https://github.com/geopandas/geopandas) ![Python](resources/icon/python.png) - Python tools for geographic data
- [Pyproj](https://github.com/jswhit/pyproj) ![Python](resources/icon/python.png) - Python interface to PROJ4 library for cartographic transformations
- [GeoDjango](http://geodjango.org/) ![Python](resources/icon/python.png) - Django geographic web framework.
- [Rasterstats](https://github.com/perrygeo/python-rasterstats/) ![Python](resources/icon/python.png) - Python module for summarizing geospatial raster datasets based on vector geometries.
- [xarray](http://xarray.pydata.org/en/stable/) ![Python](resources/icon/python.png) - xarray (formerly xray) is an open source project and Python package that aims to bring the labeled data power of pandas to the physical sciences, by providing N-dimensional variants of the core pandas data structures.
- [Cartopy](http://scitools.org.uk/cartopy/) ![Python](resources/icon/python.png) - A library providing cartographic tools for python for plotting spatial data.
- [NumPy](http://www.numpy.org/) ![Python](resources/icon/python.png) - NumPy is the fundamental package for scientific computing with Python.
- [matplotlib](http://matplotlib.org/) ![Python](resources/icon/python.png) - Python 2D plotting library.
- [Scikit-image](http://scikit-image.org/) ![Python](resources/icon/python.png) - Scikit-image is a collection of algorithms for image processing.
- [pyWPS](http://pywps.org/) ![Python](resources/icon/python.png) - An implementation of the Web Processing Service standard from the Open Geospatial Consortium. PyWPS is written in Python. It enables integration, publishing and execution of Python processes via the WPS standard.
- [pyCSW](http://pycsw.org/) ![Python](resources/icon/python.png) - Fully implements the OpenGIS Catalogue Service Implementation Specification (Catalogue Service for the Web). Initial development started in 2010 (more formally announced in 2011). The project is certified OGC Compliant, and is an OGC Reference Implementation.
- [Peartree](https://github.com/kuanb/peartree) ![Python](resources/icon/python.png) - Peartree: A library for converting transit data into a directed graph for network analysis.


## Open Forums and communities
| ▲ [Top](#awesome-gis) |
| --- |
- **Conference**
  - [Esri International User Conference](http://www.esri.com/events/user-conference)
  - [Esri Developer Summit](http://www.esri.com/events/devsummit)
  - [FOSS4G](http://foss4g.org/)
  - [State of the Map](https://stateofthemap.org/)

- **Communities**
  - [OGC](http://www.opengeospatial.org/) - an international not for profit organization committed to making quality open standards for the global geospatial community

- **Open Standards**
  - [3D Tiles](http://www.opengeospatial.org/standards/3DTiles)
  - [Cat: ebRIM App Profile: Earth Observation Products](http://www.opengeospatial.org/standards/cat2eoext4ebrim)
  - [Catalogue Service](http://www.opengeospatial.org/standards/cat)
  - [CDB](http://www.opengeospatial.org/standards/cdb)
  - [CityGML](http://www.opengeospatial.org/standards/citygml)
  - [Filter Encoding](http://www.opengeospatial.org/standards/filter)
  - [GML in JPEG 2000](http://www.opengeospatial.org/standards/gmljp2)
  - [GeoAPI](http://www.opengeospatial.org/standards/geoapi)
  - [GeoPackage](http://www.opengeospatial.org/standards/geopackage)
  - [Geography Markup Language](http://www.opengeospatial.org/standards/gml)
  - [GeoRSS](http://www.opengeospatial.org/standards/georss)
  - [KML](http://www.opengeospatial.org/standards/kml)
  - [Mapbox Vector Tile](https://github.com/mapbox/vector-tile-spec)
  - [NetCDF](http://www.opengeospatial.org/standards/netcdf)
  - [OWS Context](http://www.opengeospatial.org/standards/owc)
  - [Styled Layer Descriptor](http://www.opengeospatial.org/standards/sld)
  - [Symbology Encoding](http://www.opengeospatial.org/standards/se)
  - [Web Coverage Service](http://www.opengeospatial.org/standards/wcs)
  - [Web Feature Service](http://www.opengeospatial.org/standards/wfs)
  - [Web Map Service](http://www.opengeospatial.org/standards/wms)
  - [Web Map Tile Service](http://www.opengeospatial.org/standards/wmts)
  - [Web Processing Service](http://www.opengeospatial.org/standards/wps)

## Awesome-Awesomeness
| ▲ [Top](#awesome-gis) |
| --- |
- [awesome-vector-tiles](https://github.com/mapbox/awesome-vector-tiles) - awesome implementations of the Mapbox Vector Tile specification.
- [awesome-satellite-imagery-datasets](https://github.com/chrieke/awesome-satellite-imagery-datasets) - List of satellite imagery datasets with annotations for computer vision and deep learning.
- [awesome-earthobservation-code](https://github.com/elasticlabs/awesome-earthobservation-code) - curated list of awesome tools, tutorials, code, helpful projects, links, stuff about Earth Observation and Geospatial stuff!
