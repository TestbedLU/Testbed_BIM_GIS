# Calculation of building footprint area for IFC-models
Custom transformers:

- __FootprintAreaCalculator.fmx__
- __FootprintAreaCalculator_IfcSpace.fmx__

__FootprintAreaCalculator.fmx__ is used in workspace *Hjaltevadshus Spira 168 - without object for BUA.fmw*, *Hjaltevadshus Spira 175 - without object for BUA.fmw*, *House45* and *KTHDemohouse*.

__FootprintAreaCalculator_IfcSpace.fmx__ is used in workspace *Kamakura - with object for BUA.fmw*.

Workspace *Multihuset - without object for BUA.fmw* uses __FootprintAreaCalculator.fmx__ but not as a custom transformer and with some modification.


## Calculation without object representing BUA (Building area)

### House45
House model specially produced by Martin Hooper at Sweco Positon for calculation of building height.

<img src="https://github.com/TestbedLU/Testbed_BIM_GIS/blob/master/Building%20footprint%20area/House%2045/House45.PNG" width="189" height="104">

### KTHDemohouse
Building model produced at KTH (Kungliga Tekniska Högskolan) division of project communication.

<img src="https://github.com/TestbedLU/Testbed_BIM_GIS/blob/master/Building%20footprint%20area/KTHDemohouse/KTHfront.PNG" width="204" height="129">

### Hjaltevadhus
Two models of singel family homes, Spira 168 and Spira 175, produced by house manufacturers [Hjältevadshus](https://hjaltevadshus.se/hus/).

<pre><b>Spira 168                  Spira 175</b></pre>

<img src="https://github.com/TestbedLU/Testbed_BIM_GIS/blob/master/Building%20footprint%20area/Hjaltevadshus/Pictures%20-%20house%20models/Hjaltevad168front.PNG" width="203" height="126"> <img src="https://github.com/TestbedLU/Testbed_BIM_GIS/blob/master/Building%20footprint%20area/Hjaltevadshus/Pictures%20-%20house%20models/Hjaltevad175front.PNG" width="209" height="128">


### Multihuset
A large house with many different uses.

<img src="https://github.com/TestbedLU/Testbed_BIM_GIS/blob/master/Building%20footprint%20area/Multihuset/Pictures%20-%20house%20models/multihus3.PNG" width="205" height="118">


## Calculation with object representing BUA

### Kamakura House
Singel family home, produced by Martin Hooper at Sweco Position.

<img src="https://github.com/TestbedLU/Testbed_BIM_GIS/blob/master/Building%20footprint%20area/Kamakura%20House/kamakura1.PNG" width="207" height="168">

## Links

[Master Thesis - Automation of building permit applications](http://lup.lub.lu.se/student-papers/record/8954066)

## License
*BSD 3-Clause License*

*Copyright (c) 2018, TestbedLU*
*All rights reserved.*

See the [LICENSE.md](https://github.com/TestbedLU/Testbed_BIM_GIS/blob/master/LICENSE) file for details.
