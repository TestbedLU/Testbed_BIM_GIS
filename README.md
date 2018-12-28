# Testbed_BIM_GIS
This testbed contains FME scripts/custom transformers which handles conversion of IFC files to mesh, conversion between IFC and SGP (Swedish geoprocess) and calculations of building footprint area and height of a building model (IFC). For each script/custom transformer there is a document "Description and usage" that describes the script (in English). Annotations in the scripts are either in Swedish or English.

__Content__:
1.  IfcToMesh
2.  Building footprint area
    - Hjaltevadshus
    - Multihuset
    - House 45
    - KTHDemohouse
    - Kamakura House
3.  Building height
4.  Detailed development plan reader
5.  Conversion IFC to SGP 3.0 - Geometry and Writer
    - LOD1
    - LOD2
7.  Combined script (2,3,4,5)

## Data
Some scipts are published without input data due to restrictive license rules.
Scripts with attached data:
* House 45
* KTHDemohouse
* Building height
* Combined script

__House45__

Source: Martin Hooper, Sweco Position Malmö

__KTHDemohouse__

Source: KTH, division of project communication.

__Höganäs detaljplan - ArildCentral__

Source: Höganäs municipality, Urban planning office.

__Digital Elevation Model__

Source: Artificially created DEM

## Built with
[FME](https://www.safe.com/) - Safe Software

## Links

[Article - Automation of Building Permission by Integration of BIM and Geospatial Data](https://www.mdpi.com/2220-9964/7/8/307)

[Master Thesis - Automation of building permit applications](http://lup.lub.lu.se/student-papers/record/8954066)

## License

*BSD 3-Clause License*

*Copyright (c) 2018, TestbedLU*
*All rights reserved.*

See the [LICENSE.md](https://github.com/TestbedLU/Testbed_BIM_GIS/blob/master/LICENSE) file for details.
