# Awesome ArcGIS Developer

An awesome set of resources to help you with ArcGIS Platform development, APIs, SDKs, tools, and location services.

> **Notes**: [Code of conduct](CODE_OF_CONDUCT.md) | [Contributing](CONTRIBUTING.md) | Licensed under the [Apache 2.0 license](LICENSE.md).

---

**TABLE OF CONTENTS**

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [APIs and SDKs](#apis-and-sdks)
- [Cartographic generalization](#cartographic-generalization)
- [Code samples and snippets](#code-samples-and-snippets)
- [Data format conversion tools](#data-format-conversion-tools)
- [Data exploration and manipulation](#data-exploration-and-manipulation)
- [Data integration tools](#data-integration-tools)
- [Debugging tools](#debugging-tools)
- [Design](#design)
- [Related awesome lists](#related-awesome-lists)
- [Specifications](#specifications)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

---

## APIs and SDKs

- [ArcGIS API for JavaScript](https://developers.arcgis.com/javascript/latest/): guides, sample code, API references and showcase to build 2D and 3D interactive web apps unlocking geospatial data.
- [ArcGIS API for Python](https://developers.arcgis.com/python/): guides, sample notebooks and API reference to do mapping, spatial analysis, data science, geospatial AI and automation using Python.
- [ArcGIS Earth Automation API](https://doc.arcgis.com/en/arcgis-earth/automation-api/get-started.htm): guide, API reference and samples to communicate with ArcGIS Earth.
- [ArcGIS Enterprise SDK](https://developers.arcgis.com/enterprise-sdk/): guides, API refence and sample code to extent ArcGIS Enterprise.
- [ArcGIS Pro SDK for Microsoft .NET](https://pro.arcgis.com/en/pro-app/latest/sdk/): documentation, tutorials, API reference, FAQ, etc. to extend ArcGIS Pro Desktop.
- [ArcGIS REST APIs](https://developers.arcgis.com/rest/): general documentation about ArcGIS REST APIs: location services, content management, portal administration, and more.
- [ArcGIS REST JS](https://developers.arcgis.com/arcgis-rest-js/): key concepts, tutorials and API reference of a collection of JavaScript modules for accessing location services, ArcGIS Online, and ArcGIS Enterprise REST APIs.
- [ArcGIS Runtime API for .NET](https://developers.arcgis.com/net/): guides, sample codes and API reference to build desktop and mobile apps using .Net.
- [ArcGIS Runtime API for Android](https://developers.arcgis.com/android/): guides, sample codes and API reference to build mobile apps using Java or Kotlin.
- [ArcGIS Runtime API for iOS](https://developers.arcgis.com/ios/): guides, sample codes and API reference to build mobile apps using Swift or Objective-C.
- [ArcGIS Runtime API for Java](https://developers.arcgis.com/java/): guides, sample codes and API reference to build desktop apps.
- [ArcGIS Runtime API for Qt](https://developers.arcgis.com/qt/): guides, sample codes and API reference to build mobile and desktop apps.
- [ArcGIS Urban API](https://developers.arcgis.com/arcgis-urban-api/): public GraphQL web service that can be used to interact with ArcGIS Urban data directly.
- [ArcObjects SDK for .Net](https://desktop.arcgis.com/en/arcobjects/latest/net/webframe.htm#RoadmapToExtendingArcObjects.htm): documentation about the .Net SDK for the library of Component Object Model (COM) components that make up the foundation of ArcGIS.
- [ArcObjects SDK for Java](https://desktop.arcgis.com/en/arcobjects/latest/java/#80146cac-6b50-4c82-a9f5-7a5be3406c5b.htm): documentation about the Java SDK for the library of Component Object Model (COM) components that make up the foundation of ArcGIS.
- [ArcPy](https://pro.arcgis.com/en/pro-app/arcpy/main/arcgis-pro-arcpy-reference.htm): documentation about the python package to perform geographic data analysis, data conversion, data management, and map automation in ArcGIS Desktop or ArcGIS Enterprise environments.
- [Esri Leaflet](https://developers.arcgis.com/esri-leaflet/): key concepts, tutorials, API reference, plugins, sample code to help you build web apps using Leaflet with ArcGIS Location services.
- [MapboxGL JS](https://developers.arcgis.com/mapbox-gl-js/): guide and tutorials to help you start building web apps with Mapbox and ArcGIS location services.
- [OpenLayers](https://developers.arcgis.com/openlayers/): guide and tutorials to help you start building web apps with OpenLayers and ArcGIS location services.

## Cartographic generalization

- [Distillery](http://shancarter.github.io/distillery/): web application to simplify and project TopoJSON.
- [Feature Service Layer](https://developers.arcgis.com/rest/services-reference/enterprise/query-feature-service-layer-.htm): the `maxAllowableOffset` parameter can be used for generalizing geometries returned by the `query` operation.
- [Generalize method](https://bit.ly/2VNPkuO): GeometryEngine can produce a geometry with fewer vertices programatically. Several APIs supports it: JavaScript, iOS, Android, .NET, Qt and Java.
- [PostGIS ST_Simplify](https://postgis.net/docs/ST_Simplify.html): this operation returns a "simplified" version of the given geometry using the Douglas-Peucker algorithm.

## Code samples and snippets

- [ArcGIS API for JavaScript Sample Code](https://developers.arcgis.com/javascript/latest/sample-code/): official Esri's JavaScript API product team samples.
- [ArcGIS Code Sharing](http://codesharing.arcgis.com/): search, browse, and use code, scripts, models, add-ins, widgets, and more.
- [Esri/arcgis-js-vscode-snippets](https://github.com/Esri/arcgis-js-vscode-snippets): Collection of Visual Studio Code snippets for common code patterns.
- [Esri/developer-support](https://github.com/Esri/developer-support): community samples to help be successful with all ArcGIS developer products (Python, NET, JavaScript, Android…).
- [Esri/jsapi-resources](https://github.com/Esri/jsapi-resources) A collection of resources for developers using the [ArcGIS API for JavaScript](https://developers.arcgis.com/javascript/).
- [esrinederland/CoolMaps](https://github.com/esrinederland/CoolMaps): shows cool example maps you can use.
- [esrinederland/CoolScripts](https://github.com/esrinederland/CoolScripts): Esri Netherlands scripts and snippets for reuse.
- [RalucaNicola/code-snippets-arcgis-api-js](https://github.com/RalucaNicola/code-snippets-arcgis-api-js): A collection of code snippets for ArcGIS API for JavaScript.

## Data format conversion tools

- [arcgis-json-to-geojson](https://github.com/gavinr/arcgis-json-to-geojson): convert layer in ArcGIS JSON spec to GeoJSON spec.
- [csv2geojson](https://viglino.github.io/ol-ext/examples/misc/csv2geojson.html): convert points from CSV format to GeoJSON.
- [gdal](https://github.com/OSGeo/gdal): translator library for raster and vector geospatial data formats.
- [geojson2svg](https://github.com/w8r/geojson2svg): render GeoJSON into SVG using inline or external stylesheet.
- [geojsonio](https://github.com/ropensci/geojsonio): convert many data formats to and from GeoJSON and TopoJSON.
- [gtfs2geojson](https://github.com/node-geojson/gtfs2geojson): Convert GTFS data into GeoJSON.
- [Koop](https://koopjs.github.io): JavaScript toolkit for connecting spatial APIs. Transform geospatial data on the fly and serve as GeoJSON, Vector Tiles, Feature Services and more.
- [loam](https://github.com/azavea/loam): JavaScript wrapper for GDAL in the browser.
- [terraformer](https://github.com/terraformer-js/terraformer) convert ArcGIS JSON to and from GeoJSON, convert WKT geometries to and from GeoJSON geometries, and other formats.
- [togeojson](https://mapbox.github.io/togeojson/): convert KML and GPX to GeoJSON, without the fuss.
- [tokml](https://github.com/mapbox/tokml): convert GeoJSON to KML.

## Data exploration and manipulation

- [ArcGIS Web Map Viewer](https://www.arcgis.com/apps/mapviewer/index.html): web application to create, explore, and share web maps for 2D applications.
- [ArcGIS Web Map Viewer (classic version)](https://arcgis.com/home/webmap/viewer.html): web application to create, explore, and share web maps for 2D applications.
- [ArcGIS Web Scene Viewer](https://www.arcgis.com/home/webscene/viewer.html): web application to create, explore, and share web maps for 3D applications.
- [geojson.io](https://github.com/mapbox/geojson.io): web application to generate and edit geospatial vector data. Supports GeoJSON, TopoJSON, CSV, KML, WKT, and shapefile.
- [Mapshaper](https://github.com/mbloch/mapshaper): web application to simplify shapes, edit attribute data, clipp, erase, dissolve, filter, etc. Supported file formats: Shapefile, GeoJSON, TopoJSON and CSV files. 
- [Smart Mapping](https://www.esri.com/en-us/smart-mapping): is built-in in the Map and Scene viewer, but some APIs like JavaScript and Python also provide utilities to help building data explorations tools.

## Data integration tools

- [ArcGIS Data Interoperability Extension](https://esri-es.github.io/awesome-arcgis/arcgis/products/extensions/data-interoperability/): desktop tool to transform +400 data formats. 
- [FME Server](https://www.safe.com/integrate/): ETL allowing to easily transform almost any dataset into an ArcGIS compatible format and vice-versa. Support for 500+ formats and technologies.
- [Integromat](https://www.integromat.com/en/integrations/survey123): iPaas to automate repetitive tasks involved in using Survey123 and make your work easier.
- [node-red-contrib-arcgis-rest](https://flows.nodered.org/node/node-red-contrib-arcgis-rest): query, delete, update or insert data with low-code programming for event-driven applications of the JS Foundation.
- [Zapier for ArcGIS](https://marketplace.arcgis.com/listing.html?id=5ab7936269f8449b82b0f5c78695ab38): iPaaS to automate integrations without writing any code.
- [Tray.io](https://tray.io/connectors/arcgis-integrations): Manual, scheduled and webhook triggers to apply edits, get features, layers, etc. using Tray Platform’s ArcGIS connector.

## Debugging tools

- [Fiddler Classic](https://www.telerik.com/fiddler/fiddler-classic): Windows tool that logs HTTP(s) network traffic.
- [GeoJSONLint](https://geojsonlint.com/): validate and view your GeoJSON.
- [json-schema.org](https://json-schema.org/): vocabulary that allows you to annotate and validate JSON documents (include multiple validators).
- [mapbox/geojson-vt/debug](http://mapbox.github.io/geojson-vt/debug/): validate GeoJSON or TopoJSON.
- [Postman interceptor](https://www.postman.com/product/postman-interceptor/): interceptor enables you to sync cookies from your browser and capture network requests directly from Chrome.
- [test-cors.org](https://test-cors.org): app to test CORS requests. You can either send the CORS request to a remote server (to test if CORS is supported), or send the CORS request to a test server (to explore certain features of CORS).
- [netbalancer.com](https://netbalancer.com/): Windows application for local network traffic control and monitoring.

## Design

- [ArcGIS Vector Tile Style Editor](https://developers.arcgis.com/documentation/mapping-apis-and-services/tools/vector-tile-style-editor/): Style vector tile basemap layers for applications.
- [arcgis-vectortile-style-editor](https://github.com/Esri/arcgis-vectortile-style-editor): minimalistic tool to update the styles of Esri Vector Basemaps through JSON.
- [Calcite Design System](https://developers.arcgis.com/calcite-design-system/): collection of mapping icons, web components, and good practices.
- [EsriUK mapstyler](https://github.com/EsriUK/mapstyler): quickly style an Esri vector tile layer using an image.
- [MapUIPatterns](https://www.mapuipatterns.com/): best practices & design principles. UI Patterns describe solutions to observed and recurring design problems.

## Related awesome lists

- [awesome-arcgis](https://github.com/esri-es/awesome-arcgis/): awesome list with a wiki flavor with resources about Esri and ArcGIS organized by: products, industries, file formats, content providers, etc.
- [awesome-earthobservation-code](https://github.com/acgeospatial/awesome-earthobservation-code): tools, tutorials, code, helpful projects and links about Earth Observation and Geospatial stuff.
- [awesome-geojson](https://github.com/tmcw/awesome-geojson): GeoJSON utilities: operations,editors & viewers, validation, services, conversion, etc.
- [awesome-geospatial](https://github.com/sacridini/Awesome-Geospatial): databases, radar, lidar, web map development, etc.
- [awesome-gis](https://github.com/sshuair/awesome-gis): GIS, remote sensing, 3D apps, Web Map Servers, Geospatial libraries, Open Standards , data, etc.
- [awesome-json-datasets](https://github.com/jdorfman/awesome-json-datasets): JSON datasets that don't require authentication about: climate, crime, goverment, NASA, travel, etc.
- [awesome-open-geoscience](https://github.com/softwareunderground/awesome-open-geoscience): curated from repositories that make our lives as geoscientists, hackers, and data wranglers easier or just more awesome.
- [awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets): a topic-centric list of high-quality open datasets.
- [awesome-remote-sensing-change-detection](https://github.com/wenhwu/awesome-remote-sensing-change-detection): list of datasets, codes, and contests related to remote sensing change detection.
- [awesome-satellite-imagery-datasets](https://github.com/chrieke/awesome-satellite-imagery-datasets): list of satellite image training datasets with annotations for computer vision and deep learning.
- [awesome-semantic-segmentation](https://github.com/mrgloom/awesome-semantic-segmentation): networks by architecture (semantic segmentation, instance aware segmentation, ...), RNN, GANS, datasets, etc.
- [awesome-vector-tiles](https://github.com/mapbox/awesome-vector-tiles): implementations of the Mapbox Vector Tile specification: parsers & generators, clients, apps and command line tools, CLI utilities, servers, etc.

## Specifications

- [Cartographic Information Model spec](https://github.com/Esri/cim-spec): map content specification used to persist and transfer cartographic descriptions of GIS datasets represented in JSON.
- [Common data types](https://developers.arcgis.com/documentation/common-data-types/geometry-objects.htm): JSON formats of the geometry and spatial reference objects as returned by ArcGIS REST API: Point, Multipoint, Polyline, Polygon and Envelope. 
- [GeoServices spec](https://github.com/koopjs/FeatureServer): Open Web Foundation REST-based API that provides a complete access to structured geospatial data used by Esri.
- [Indexed 3D Scene Layers](https://github.com/Esri/i3s-spec): service and package standard of containers for arbitrarily large amounts of geographic data.
- [Shapefile Format](https://www.esri.com/content/dam/esrisites/sitecore-archive/Files/Pdfs/library/whitepapers/pdfs/shapefile.pdf): spec for the geospatial vector data format for GIS software.
- [Spatial reference specifications](https://developers.arcgis.com/documentation/spatial-references/#spatial-reference-specifications): list of  Well-Known ID (WKID) integer value or a text string definition referred to as Well-Known Text (WKT) to define a spatial reference.
- [Tile Package Specification](https://github.com/Esri/tile-package-spec): compressed file containing a set of tiles and a tiling scheme, which can be used as a basemap in ArcGIS applications.
- [Web Map spec](https://developers.arcgis.com/web-map-specification/): sharable 2D maps. It describes the JSON object which defines a web map.
- [Web Scene spec](https://developers.arcgis.com/web-scene-specification/): sharable 3D maps. It describes the JSON object which defines a web scene.