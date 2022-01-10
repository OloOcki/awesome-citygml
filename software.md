![!! Awesome CityGML !!](https://github.com/OloOcki/awesome-citygml/blob/main/img/awesomeGif.gif)

# :cityscape: Awesome CityGML Software :cityscape:

This list contains software supporting CityGML (open source and also proprietary).
For more lists please refer to the [freeware](https://www.citygmlwiki.org/index.php/Freeware)
 and [commercial](https://www.citygmlwiki.org/index.php/Commercial_Software) software pages of the CityGML wiki.

Please feel free to contribute or write to olaf.wysocki@tum.de!

## Viewers

- **3DCityDB-Web-Map-Client** Cesium-based 3D viewer and JavaScript API for the 3D City Database

[[Code](https://github.com/3dcitydb/3dcitydb-web-map)] [[Docker](https://github.com/tum-gis/3dcitydb-web-map-docker)]

- **azul** 3D viewer for macOS intended for viewing 3D city models in CityGML 1.0 and 2.0, CityJSON 1.0, IndoorGML, OBJ, OFF and POLY

[[Code](https://github.com/tudelft3d/azul)] [[Mac App Store](https://apps.apple.com/app/azul/id1173239678?mt=12)]

- **FZKViewer** software tool for visualization of standardized semantic data models from the fields of BIM and GIS including CityGML and ADEs

[[Website](https://www.iai.kit.edu/english/1302.php)]

## Databases

- **3D City Database** free 3D geo database to store, represent, and manage virtual 3D city models on top of a standard spatial relational database (PostgreSQL/PostGIS and Oracle Spatial/Locator)

[[Website](https://www.3dcitydb.org)] [[Code](https://github.com/3dcitydb/3dcitydb)] [[Documentation](https://3dcitydb-docs.readthedocs.io/)] [[Paper](https://doi.org/10.1186/s40965-018-0046-7)]

- **3D City Database Importer/Exporter** Java based client for importing and exporting datasets to the 3D City Database

[[Code](https://github.com/3dcitydb/importer-exporter)]

- **GeoRocket** High-performance data store for geospatial files (ready for the cloud). Supports CityGML, GML, GeoJSON, and more.

[[Website](https://georocket.io/)]

## Tools

- **citygml-tools** command line utility that bundles several operations (e.g. validation, appearance removal) for processing CityGML files

[[Code](https://github.com/citygml4j/citygml-tools)]

- **CityLDT** tool for upscaling or downscaling geometries of 3D spatial CityGML building models

[[Code](https://gitlab.e3d.rwth-aachen.de/e3d-software-tools/cityldt/cityldt)]

- **FME** general purpose data integration platform for visualizing and transforming data with custom workflows

[[Website](https://www.safe.com/fme/)]

- **r:trån** road space model transformer library for OpenDRIVE, CityGML

[[Website & documentation](https://rtron.io)] [[Code](https://github.com/tum-gis/rtron)] [[Paper](https://doi.org/10.3390/su12093799)]

## Libraries

- **citygml4j** open source Java library for developing CityGML-aware software applications

[[Code](https://github.com/citygml4j/citygml4j)]

- **libcitygml** small and easy to use open source C++ library for 3D rendering applications of CityGML files

[[Code](https://github.com/jklimke/libcitygml)]

## Validators

- **val3dity** validator of 3D primitives according to the international standard ISO19107

[[Code](https://github.com/tudelft3d/val3dity)]

- **CityDoctor** CityDoctor is a tool for validation and repair of 3D city models. That tool can check and repair the syntax, geometries and semantics of models.

[[Website](https://www.citydoctor.eu/en/citydoctor_main.html)]

## Plugins

- **CityEditor** SketchUp plugin for loading, editing and writing CityGML datasets

[[Website](https://www.3dis.de/cityeditor/)]

- **GEORES** SketchUp plugin for importing and exporting CityGML files with annotation functionalities

[[Code](https://github.com/GeoplexGIS/geores)]

## Generators

- **3dfier** takes 2D GIS datasets and "3dfies" them by lifting every polygon to 3D using point clouds for elevation information

[[Website & documentation](http://tudelft3d.github.io/3dfier/)] [[Code](https://github.com/tudelft3d/3dfier/)] [[Docker](https://hub.docker.com/r/tudelft3d/3dfier)] [[Paper](https://doi.org/10.21105/joss.02866)]

- **Random3Dcity** basic procedural modelling engine for generating random (synthetic) buildings and other features in CityGML in multiple levels of detail (LOD)

[[Code](https://github.com/tudelft3d/Random3Dcity)] [[Paper](http://doi.org/10.5194/isprs-annals-IV-4-W1-51-2016)]

- **VCS BuildingReconstruction** commercial tool for the generation of large-scale 3D city models in LoD1 and LoD2.

[[Website](https://vc.systems/en/products/building-reconstruction/)]

- **osm2citygml** This tool will take XMLs of buildings from OSM using Overpass and convert it to CityGML format with OSM2World and FME for eventual use with 3DCityDB.

[[Code](https://github.com/cuulee/osm2citygml)]

- **RhinoCity** produce, edit and analyze textured 3D city models.

[[Website](https://www.rhinoterrain.com/en/rhinocity.html)]
