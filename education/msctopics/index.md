---
layout: page
title:  Potential MSc topics
permalink: /education/msctopics/
---

<div class="alert alert-success text-center" role="alert">
  <b>Heads up!</b> Theses done in our group should follow the <a href="https://3d.bk.tudelft.nl/courses/geo2020/openscience/">requirements for open science</a>.
</div>

- - -

* Table of Content
{:toc}

- - -

## Towards true 3D noise calculations

![](img/3d_noise_software.png){:width="400px"}

The current implementations of noise calculation software simplify the environment into cross sections and 2D calculations. Such simplifications were necessary at the times when these software were created in order to make the calculations computationally feasible. Since then both hardware and algorithms evolved, potentially opening the door toward true 3D noise calculations.

The aim is to investigate how could we create a modern, efficient, true 3D noise calculation software, and if the added complexity is justified by the improved accuracy. Special attention needs to be given to make sure that noise experts are able to verify the correctness of the software.

This is a software focused project, in which you can expect to explore the geometry of sound propagation, 3D computations, data structures, learn the details of the European noise assessment method (CNOSSOS-EU) and/or the Dutch method.

This topic continues the work of the synthesis project *3D noise simulation based on advanced input data using automatically generated TINs* and is closely related to our research on [Automated reconstruction of 3D input data for noise studies](https://3d.bk.tudelft.nl/projects/noise3d/).

Potentially in collaboration with [RIVM](https://www.rivm.nl/) and/or [RWS](https://www.rijkswaterstaat.nl/).

**Contact:** [Balázs Dukai](http://balazsdukai.com/) and someone

- - - 

## How much detail is too much for 3D noise calculations?

![](img/3d_noise_data.png){:width="400px"}

People generally assume that more detail leads to higher accuracy, also in noise calculations. However, there is no clear consensus on what is sufficient or superfluous when it comes to the geometric detail of input data. This makes it difficult to create a standardized input data set for noise calculations. 

The aim is to find out to what extent does the inclusion of more data detail improve the 3D noise calculations while staying computationally feasible. We are particularly interested in the geometric detail in terrain, buildings, ground types, bridges, noise barriers and any other object prescribed by the noise calculation method.

This is a data driven project in which you can expect to run many noise calculations, explore and investigate data sets, create your own data sets, learn the details of the European noise assessment method (CNOSSOS-EU) and/or the Dutch method.

This topic continues the work of the synthesis project *3D noise simulation based on advanced input data using automatically generated TINs* and is closely related to our research on [Automated reconstruction of 3D input data for noise studies](https://3d.bk.tudelft.nl/projects/noise3d/).

Potentially in collaboration with [RIVM](https://www.rivm.nl/) and/or [RWS](https://www.rijkswaterstaat.nl/).

**Contact:** [Balázs Dukai](http://balazsdukai.com/) and someone

- - -

## Web application for Urban Computational Fluid Dynamics Simulations Set-Up validation.

Performing computational fluid dynamics (CFD) simulations in urban environments entails many pre-run set-up features that can have a drastic impact in the simulations performance. For example, the extension of the domain should be large enough to limit blockage around the buildings, or the mesh resolution should be refined enough to ensure the flow results grid independence. Many of these pre-run processes can be partially automatic, and tools that quickly check if the simulation set-up respects the CFD guidelines can be developed.

In this MSc thesis we will develop a web application that allows to import CFD set-ups from users and check their compatibility with the most up to data CFD guidelines developed by the wind engineering community. The application will analyze the set-up and report back to the user with potential improvements, if needed. 

If you work on this topic, you can expect to learn about CFD best practice guidelines, set-ups and flow simulations, as well as web development. Programming experience and interest is an advantage for this topic. Your work will require to implement source code for the analysis of the set-ups (in C++ or Python) and the web interface (in HTML and JavaScript). 

![](img/DomainandDirectionandMeshClean.png){:width="400px"}

**Contact:** [Clara García-Sánchez](https://cgarcia-sanchez.com) and [Stelios Vitalis](http://3d.bk.tudelft.nl/svitalis).

- - -

## Testing and extension of a GIS-supported design tool for new urban development areas

![](img/ga_giscity_2020.jpg){:width="600px"}

The thesis builds upon work carried out in a previous MSc [thesis](http://resolver.tudelft.nl/uuid:844b92d4-aa22-4ae7-b6c3-3b563dd3318e) - check out the [video](https://www.youtube.com/watch?v=cPYT5_cFIgw)! - in which a first prototype of a geodata-supported design tool for new urban development areas was created. The tool is coupled with semantic 3D city models as a source of integrated spatial and non-spatial information.
The thesis will focus first on thoroughly testing the existing tool and will then implement new functionalities. Possible examples are the computation of KPIs for urban analyses, 3D web-based visualisation and interaction interfaces, as well as scenarios management. The precise development focus of the thesis will be agreed upon with the student.

The research will be carried out on a selected case study and in cooperation with the Cross Domain-City of the Future graduation [studio](https://www.tudelft.nl/en/education/programmes/masters/architecture-urbanism-and-building-sciences/msc-architecture-urbanism-and-building-sciences/master-tracks/architecture/programme/studios/city-of-the-future/), which focuses on how to design and develop in an integrated way a transformation area into an attractive future urban environment.

**Contacts:** [Giorgio Agugiaro](https://3d.bk.tudelft.nl/gagugiaro/), [Roberto Cavallo](https://www.tudelft.nl/en/staff/r.cavallo) 

- - -

## Utilization of alternative fuels in the transport sector and identification of their emission reduction potential regarding harmful air pollution

The air quality in cities is one of the big topics of modern society. This air quality is affected form harmful emission like nitrogen oxides and particulate matter that are, in urban areas, mainly produced from the transport sector. A promising option besides changing the modal split or reducing mileages is the change to alternative fuels. To identify suitable application cases for alternative fuels, analyses to determine which vehicles are the main polluters in agglomerations are mandatory. 

In the framework of this master thesis, you will work independently with a model developed at the Forschungszentrum Jülich that considers the mileages and resulting emissions of road transport, rail transport, inland waterway transport and air transport considering different fuels and conditions. Mileages and emissions are spatially presented in the results of the model. Your work will include development and extension of this model as well as the analysis of results for different future scenarios. The model is implemented in Python and QGIS is used to plot results.

This project is done in cooperation with Forschungszentrum Jülich GmbH, Jülich, Germany. The work will take place in Jülich, Germany. Experience in programming and a basic in German language is beneficial, but not essential.

![](img/julich_01.jpg){:width="600px"}

**Contacts:** [Giorgio Agugiaro](https://3d.bk.tudelft.nl/gagugiaro/) (3D Geoinformation), [Janos Breuer](https://www.fz-juelich.de/SharedDocs/Kontaktdaten/Mitarbeiter/B/Breuer_ja_breuer_fz_juelich_de.html?nn=557474) (Forschungszentrum Jülich, Germany)

- - -

## Coupling 3D city models with Ladybug tools for environmental analyses

<img src="img/ga_ladybug.jpg" style="width: 600px;"/>

The MSc thesis will focus on interoperability between the Ladybug tools and semantic 3D city models encoded in CityJSON and extended with the Energy ADE. The [Ladybug Tools](https://www.ladybug.tools/) are a collection of free applications that support environmental design and education. They are among the most comprehensive, connecting 3D Computer-Aided Design (CAD) interfaces to a host of validated simulation engines. The thesis builds upon a previous [MSc thesis](https://repository.tudelft.nl/islandora/object/uuid:fb35db7c-9af8-488c-8d0b-263b138d8fd3) completed in 2020.

Particular attention will be paid to energy-related topics in order verify how and to which extent the CityGML [Energy ADE](http://www.citygmlwiki.org/index.php/CityGML_Energy_ADE) (Application Domain Extension) can be used to deliver and store additional energy-related data needed by the Ladybug tools.

The students’ task will consist in choosing (together with the supervisors) a specific application covered by a Ladybug tool, to analyse the software and data requirements of the selected Ladybug tool(s) and to perform a mapping to underlying CityGML/Energy ADE data models. In addition, proper interfaces will have to be developed and tested by means of a concrete case study. This topic is available for up to *two students* (each one choosing a different application area).

**Contact**: [Giorgio Agugiaro](https://3d.bk.tudelft.nl/gagugiaro/) and [Hugo Ledoux](https://3d.bk.tudelft.nl/hledoux/)

- - -

## GIS-based integrated modelling of building stock and supply networks for assessment of near-zero energy districts

This MSc thesis topic will be jointly supervised by staff of the 3D Geoinformation group (Dept. of Urbanism) and the Climate Design group (Dept. of Architectural Engineering and Technology). Ideally, two students (one for each research group) will work together, however focusing each on one of the following topics:

![](img/energy2019.jpg){:width="600px"}

For the Geomatics track, the focus will be on modelling the building stock and the (energy) supply networks of a district in an integrated GIS environment. CityGML and its extensions Energy ADE and Utility Network ADE will be considered for the purpose. At least a basic knowledge of CityGML is required for this topic.
The focus of the energy track will be on developing a GIS-based Urban Energy Model (UEM) which simulates the building energy performance on the urban-scale. While the building  energy efficiency is getting greater attention, there is a lack of building energy simulation on the urban scale. The UEM has to be computationally efficient and simultaneously use a set of input parameters that is aggregated to a level which is proportional with the urban GIS data. This will make the model suited for the macro-level simulations. The data relates to the basic building information such as wall and window areas, shading coefficients, material properties, floor area, lighting density, internal heat production from appliances, plug loads, and occupancy schedules. 
The above-mentioned GIS-model will be integrated with the UEM, as well as design algorithm, in order to extract suitable data to be used as input to the energy models. The GIS platform collected and synthesized the data and then will be used as the input of the UEM to get energy use of buildings in the area. The model will also be applied to evaluate the energy savings of desired retrofit scenarios.
In case only one or more than 2 students are interested in this MSc thesis, specific arrangements will be made together with the supervisors.

**Contact:** [Giorgio Agugiaro](https://3d.bk.tudelft.nl/gagugiaro/) (3D Geoinformation), [Michiel Freemouw](https://www.tudelft.nl/en/staff/m.a.fremouw/) (Climate Design and Sustainability group)

- - -

## Improving automatic meshing for buildings

![](img/MeshConceptCFD.png){:width="600px"}
Computational fluid dynamic simulations require detailed meshes that can represent obstacles features accurately. In numerical simulations, the quality of the mesh can draw the line between good and poor results. Nowadays, mesh tools are general and they are not necessarily optimised for meshing entire cities, requiring large time investments to design and improve the mesh quality.

This MSc project focuses on developing an algorithm that create the mesh automatically around buildings by specifying a limited number of parameters that define the grid cells sizes. The mesh will be generated from a top-up perspective, initially extruding the geometrical edges to create cell layers close to the buildings. The approach will be first tested in 2D single and multiple building geometries.

Knowledge of programming in python is required.
Following elective course GEO5013 is an advantage.

**Contact:** [Clara Garcia-Sanchez](mailto:C.Garcia-Sanchez@tudelft.nl) and [Hugo Ledoux](http://tudelft.nl/hledoux)


- - -

## Modelling tree topology effects on wind

![](img/FlowAroundTrees.png)

Urban landscapes incorporate vegetation elements that serve for different purposes. In open spaces trees can be used to ameliorate air quality, while in other locations they can help to mitigate heat island effects or to improve pedestrian wind comfort. Flow simulations in urban canopies usually oversight resolving tree structures. However, trees have been shown to always affect the wind flow, in some cases with non-negligible impacts.

In this MSc thesis we will simulate explicitly the wind around diverse tree topologies. The results will be compared with standard approaches that approximate the drag imposed by the tree on the wind flow. The study goal is twofold: 1) we will analyze the effect of different tree shapes, and their impact on the flow structure; 2) we will evaluate the performance of  traditional drag approaches and explore potential improvements.

Knowledge of programming in python is highly desirable.

**Contact:** [Clara Garcia-Sanchez](mailto:C.Garcia-Sanchez@tudelft.nl)

- - -

## Inferring the needed building permission from a 3D building model

![](img/dormersrotterdam.png){:width="400px"}

In the Municipality of Rotterdam the building regulations are very different if a construction work on a roof is a dormer, an additional floor, or something else. It can be difficult to figure out what regulations apply for a given construction plan. To make this easier the municipality of Rotterdam would like to offer a tool that can automatically determine what permits are needed, given a 3D geometry of the building plans. The tool should be able to infer what kind of object is designed and provide to the designer the needed regulations and constraints.

In this research the aim is:
- to build a web application that can read an LoD2 CityJSON model of the current situation and allows the user to modify the building with the desired modifications;
- to develop a method that can infer what kind of object was designed in the web application (only objects on the roof will be considered) and deliver the related regulations accordingly.

**Contact:** [Francesca Noardo](http://www.noardo.eu) and [Stelios Vitalis](http://3d.bk.tudelft.nl/svitalis).

- - -

## 3D digital urban regulations to use GeoBIM for building permission checks

The automation of urban regulation checks for the planning use case requires the urban regulations to be archived in a digital and spatial (3D) format.
This project aims at the definition of an effective way to store those regulations digitally and spatially, for their use in checking urban regulations compliancy of new buildings through GeoBIM integrated information. The studied solution could start from extending [CityGML](https://www.citygmlwiki.org), employing [INSPIRE](https://inspire.ec.europa.eu/data-model/approved/r4618-ir/html/) data model, or other available standards.
In collaboration with [EuroSDR](http://www.eurosdr.net) and [Kadaster](https://www.kadaster.nl)

**Contact:** [Francesca Noardo](https://3d.bk.tudelft.nl/fnoardo/), [Ken Arroyo Ohori](https://3d.bk.tudelft.nl/ken) and [Jantien Stoter](http://3d.bk.tudelft.nl/jstoter)

- - -

## Extracting building/storey/dwelling/room shapes from a BIM models

![](img/UpTown5.gif){:width="400px"}

Given a Building Information Model in Industry Foundation Classes (IFC) format, it is necessary to extract useful information for automatic processes, such as the building envelope, number of dwellings, storeys or rooms in the building and the respective volumes and dimensions, for example to support compliancy check with the urban regulations.

Prior algorithmic knowlegde, recursion, graph concepts could be beneficial.

In collaboration with Municipality of Rotterdam.

**Contact:** [Ken Arroyo Ohori](https://3d.bk.tudelft.nl/ken) and [Francesca Noardo](https://3d.bk.tudelft.nl/fnoardo/)

- - -


## Quality control and fusion of point cloud datasets in the Netherlands

![](img/ahn3vsDIM.gif){:width="800px"}

There are several point cloud datasets available in the Netherlands. Apart from the well known AHN, the Dutch Kadaster maintains a national one derived from aerial imagery, and also some municipalities maintain their own point cloud (for example Rotterdam) as well as some commercial companies. These point clouds have different qualities, eg due to different acquisition techniques. And they have different acquisition dates and different update intervals. Typically the points clouds with higher quality are less often updated. 

For many applications it makes sense to use a combination of several point clouds: the highest quality point cloud where it is not outdated and the lower quality point cloud where there have been changes. The two point cloud applications that could be looked at are 1) reconstructed buildings and 2) terrain model (TIN).

The aims of this project would be to

* gain insight in the faults that occur in the different point clouds. Both consider general characteristics (eg. point density, noise, shadow, occlusion, vegetation penetration), but also some dataset specific problems. For instance in the image above we observe a part of the roof of a house that is several meters higher than it should be. Were does that error come from?

* Research what are the implications of combining different point clouds to get eg. a building/terrain dataset that is both as detailed as possible and as up-to-date as possible. It is possible to also involve other datasets like the BAG that have information on when buildings are modified. 

and possibly:

* How to prevent issues like the one in the image above? This  might involve looking into dense image matching techniques.

The project would likely require doing change detection for between the various point clouds for large areas on our linux server. 

**Contact:** [Ravi Peters](http://tudelft.nl/rypeters)

- - -

## Improving the automatic LoD2 building reconstruction from AHN3

![](img/lod2-add-spheres.jpg){:width="800px"}

We have a working method to automatically reconstruct LoD2.2/LoD1.3 buildings from the AHN3 point cloud that we are using to construct LoD2 building models for the whole of the Netherlands. These models will for example be used as input data for noise simulation, and will be available as open data as part of the next version of our [3D BAG dataset](http://3dbag.bk.tudelft.nl).

The aim of this project will be to improve/extend the method with one or several of the following items:

* The detection of primitive shapes in roof structures such as speheres and cones. Currently the method can only detect planes. If we also detect other types of primitive we will be able to create more accurate models.
* Making the method work without requiring a building footprint as input (next to the point cloud). Currently the method 'forces' the boundary of the model to exactly follow the BAG footprint. However, these are not always accurate and may include underground parts of the building that we would like to ignore.

Programming required, C++ recommended.

**Contact:** [Ravi Peters](http://tudelft.nl/rypeters)

- - -

## Point cloud normal estimation based on the 3D medial axis transform

![](img/wrong_normal_orientation.png){:width="400px"}

Point clouds, unstructured collections of 3D points in space, are nowadays collected with different acquisition methods, eg photogrammetry and LiDAR.
While current point clouds are dense and offer an accurate representation of real-world objects and landscapes, they lack structure and semantics.

The aim of this project is to properly *orient* a point cloud, ie to find an approximation of the normal at each point; this normal should point outwards.
Surface normals are essential for different processing of a point cloud, eg visualisation, shadow analysis or segmentation.

"Standard" methods, eg [that function in PCL](http://pointclouds.org/documentation/tutorials/normal_estimation.php), usually find the nearest points of a given point, fit a plane, and choose between the 2 possible normals (up or down) based on a viewpoint.
The problem is that in practice, eg with the [AHN3 dataset](http://www.ahn.nl), we do not have that information.

The topic involved building on our work with the [3D medial-axis transform (MAT)](https://3d.bk.tudelft.nl/projects/3dsm/) and use the 3D MAT of a point cloud as a base to obtain high quality normals with a proper orientation.

It is possible to use Python for this project, although some knowledge of C++ would surely help.

**Contact:** [Ravi Peters](http://tudelft.nl/rypeters) and [Hugo Ledoux](http://tudelft.nl/hledoux)

- - -

## Converting the national road network (NWB) from 2D into 3D

![](img/nwb.jpg){:width="700px"}

The National Road Dataset (Nationaal Wegen Bestand, NWB) will convert their [2D road network into 3D](https://nationaalwegenbestand.nl/nieuws/hoogte-informatie-toegevoegd-aan-nwb-voor-omgevingswet) by developing automated reconstruction algorithms based on LiDAR data (AHN). This is specifically challenging at the location of tunnels, bridges, viadutcs etc. This research will help in this work by developing algorithms to reconstruct the 3D NWB for the whole Netherlands. This research will be done in collaboration with the governmental authorities that are responsible for the NWB: the Nationale Databank Wegverkeergegevens (NDW) and Rijkswaterstaat, Water, Verkeer en Leefomgeving (Water, Traffic and Environment). 

*Contact:* [Ravi Peters](http://tudelft.nl/rypeters) and [Jantien Stoter](http://3d.bk.tudelft.nl/jstoter)
- - -

## 3D Cadastre

![](img/3DCadastre.png){:width="700px"}

Since more than 15 years, lots of studies have been done on 3D Cadastre to register multilevel ownership in a transparent and proper way.
In 2016, we realised the first 3D cadastral situation [3D cadastral registration]( https://3d.bk.tudelft.nl/news/2016/03/21/3DKadaster.html) in the Netherlands.
However, there is still a gap between research and practice. In this research you will analyse how a Level of Detail Framework, that defines specifc solutions for specific 3d cadatsre problems may help to close the 3D cadastre research-to-practice gap.
The idea is explained in [this](https://www.fig.net/resources/proceedings/fig_proceedings/fig2020/papers/ts04e/TS04E_stoter_ho_et_al_10503.pdf) short paper

*Contact:* [Jantien](http://3d.bk.tudelft.nl/jstoter) and [Hugo Ledoux](http://tudelft.nl/hledoux)

- - -

## Reconstructing indoor 3D models from floor plans and LiDAR point clouds 

![](img/3Dfloor.png){:width="700px"}

Some cities have acquired floor plans of individual living units in buildings. These floor plans are desribed with their 2D geometries and a floor number.
In this research you will develop and implement an algorithm that combines the floor plans with LiDAR point clouds (AHN) to reconstruct 3D building models including their indoor living untis.

*Contact:* [Jantien](http://3d.bk.tudelft.nl/jstoter) and ..........)

---

## Snap rounding in a triangulation

![](img/triangulation.png){:width="500px"}

The most common way to do edge-matching or to clean small inconsistencies within and between datasets is to apply snapping (point-to-point or point-to-line).
However, simple snapping creates many problems, including topological changes and inconsistencies.
Snap rounding extends this method in order to give robustness guarantees, but current implementations, such as [the one in CGAL](http://doc.cgal.org/latest/Snap_rounding_2/index.html), are *extremely* slow.
Related to this, in the project [pprepair](https://github.com/tudelft3d/pprepair), we have previously used a constrained triangulation as a robust method to repair polygons and planar partitions.
Using this approach topological errors are automatically fixed.
We therefore believe that using a triangulation as a base structure is an intuitive and efficient way to optimize snap rounding, since we can perform simple snapping and recover from topological errors afterwards.

The existing prototype ([pprepair](https://github.com/tudelft3d/pprepair) that needs to be extended has been developed in C++, thus the knowledge of C++---or a strong desire to learn it---is necessary.

**Contact:** [Ken Arroyo Ohori](https://3d.bk.tudelft.nl/ken)

- - -

## Instance segmentation of trees from point clouds

![](img/tree_instances.png)

Amazing techniques (e.g., [AdTree](https://github.com/tudelft3d/adtree)) have been recently proposed to 
reconstruct 3D models of real-world trees in great details. These methods assume that the tree instances 
have been segmented from the massive point clouds. However, good quality segmentation of individual trees 
is typically achieved by tedious manual work in practice. The automatic segmentation still remains an open problem. 

The aim of this thesis project is to develop a method to automatically and precisely locate and identify
individual trees in the scan of a large urban area (the TU Delft campus, for instance), allowing for 
unified processing of all the trees in the covered area. The result of the instance segmentation can be used in
various applications, e.g., detailed 3D modeling and identification of tree species.

**Required Skills**: 
Proficient in one programming language (e.g., Python or C/C++); interested and willing to follow courses in machine 
learning (in particular Deep Learning).

**Contact**: [Liangliang Nan](https://3d.bk.tudelft.nl/liangliang/)

- - -

## Integrated modelling of utility networks in the urban environment

<img src="img/ga_xander_network.jpg" style="width: 500px;"/>

In the framework of Smart Cities, the MSc thesis will focus on interoperability issues when it comes the heterogeneous utility networks (e.g. gas, water, electricity, sewage, district heating, telecommunications, etc.) that are found in the urban environment.
Starting from a CityGML-based 3D city model, the Msc. thesis will focus on testing the Utility Network ADE (Application Domain Extension) and compare it to existing or newly proposed standards (IMKL or MUDDI), based on a concrete case study which will be agreed upon with the student. 
The image shown here is taken from a previous [thesis](https://repository.tudelft.nl/islandora/object/uuid:fed24b16-cf95-4fa0-a109-ece6e91b61e9?collection=education) and serves as example - and starting point - of the overall topic of the thesis proposed here.

**Contacts**: [Giorgio Agugiaro](https://3d.bk.tudelft.nl/gagugiaro/) and [Jantien Stoter](https://3d.bk.tudelft.nl/jstoter/)

- - -

## Computation of spatial extent for massive point cloud datasets

![](img/alphashape.png)

Given a raw LAS pointcloud datasets, how to generate its [spatial extent (a polygon)](https://3d.bk.tudelft.nl/courses/backup/geo1015/2019/les/13/)?

Finding the bounding-box (or the convex hull, or with a raster solution) is in most cases not sufficient, as the image above shows.
A better solution is to use the alpha-shape of the set of points, or similar complex structures.
The problem we would be tackling here is: how to do this for a dataset of say 800M points? It doesn't fit in memory, so what can we do?

Done in collaboration with [Deltares](https://www.deltares.nl).

*Contact:* [Hugo Ledoux](https://3d.bk.tudelft.nl/hledoux) 

- - -

## Performance and robustness of software libraries for computational geometry

![](img/sweep_geometry.png){:width="500px"}

Software libraries for computational geometry underpin a lot of our research, but an in-depth comparison of how these different software libraries behave in terms of performance and robustness is not available. For example, the feasability of multi-disciplinary use of geometry in BIM/GIS integration and automated thermal analysis of IFC building models is largely shaped by the characteristics of the algorithmns offered in open source libraries such as CGAL and Open CASCADE. This research project is an opportunity to publish something novel, useful and relevant to many disciplines.

*Contact:* [Thomas Krijnen](mail@thomaskrijnen.com)

---


## Automatic repair of 3D city models

![](img/repairorientation.gif){:width="400px"}

Most 3D city models that are publicly available contain so many geometric errors (self-intersections, missing faces, duplicate vertices, etc.) that [they are more or less unusable in practice](https://speakerdeck.com/hugoledoux/how-useful-are-current-3d-city-models).

The aim of this project is to __automatically__ repair 3D city models, we can focus on the [publicly available models](https://3d.bk.tudelft.nl/opendata/opencities/) so there is plenty of data to play with.
While repair is a very-complex issue (if all cases are to be handled), this project will target the most common errors, and fix them. 
The [val3dity server](http://geovalidation.bk.tudelft.nl/val3dity/) has been logging all the validation reports for the last 4 years, so a starting point will be to analyse those and focus on what is most easy and has an impact.
Duplicate points and non-planar surfaces are pretty easy to solve; and for single polygons we [already have working code (prepair)](https://github.com/tudelft3d/prepair).
After that, more complex operators (eg [those from CGAL](https://doc.cgal.org/latest/Polygon_mesh_processing/index.html)) could be used.

The project is difficult to be done in Python, C++ is necessary (but it's a great way to improve!).
CityJSON files will be used, you will not have to deal with (the pain of parsing) CityGML files, I promise.

*Contact:* [Hugo Ledoux](https://3d.bk.tudelft.nl/hledoux)


---

## Investigate the use of CityJSON in (serious) games

![](https://media.indiedb.com/images/groups/1/23/22129/UE4Interface_5.jpg){:width="300px"}

Modern game engines, such as Unity and Unreal Engine, allow to create eye-appealing visualisations and provide tools to conduct basic analysis, such as solar potential estimation or rough flood analysis. By importing CityJSON in such an application users could explore the urban environment in a more emerging and easy way.

The aim of this project is to implement an import process for CityJSON in Unity or Unreal Engine. Then, you would have to explore the possibilities that such a technology offer when utilised with 3D city model data.

Programming knowledge in C# (for Unity) or C++ (for Unreal Engine) is required, although scripting and scene manipulation could be done with Python or the engine's graphical tools.

*Contact:* [Hugo Ledoux](https://3d.bk.tudelft.nl/hledoux) & [Stelios Vitalis](https://3d.bk.tudelft.nl/svitalis/)

---

## Building floor count determination by Convolutional Neural Network

![](https://3d.bk.tudelft.nl/ken/temp/floors-counting.jpg){:width="300px"}

Accurately knowing the number of floors of a building is an important factor when assessing the built environment. However, there is no accurate global dataset that contains this information. Simple techniques like diving the total building height by an average height per floor are sometimes used, but this obtains merely an approximation.

In collaboration with the company [Superworld](https://www.superworld.nl), the idea is to develop a method that uses images (eg Google Street View) and a base map (eg BAG in the Netherlands) to automatically derive the number of floors in a building using Convolutional Neural Networks (CNN). 

**Contact:** [Ken Arroyo Ohori](https://3d.bk.tudelft.nl/ken)

---

## Creation of a sample dataset of construction of additional floors on top of existing building

![](https://3d.bk.tudelft.nl/ken/temp/floors-addition.jpg){:width="300px"}

Additional floors are sometimes added to buildings for various reasons, such as redensification. However, this is a complex process subject to technical and legal issues.

In collaboration with the company [Superworld](https://www.superworld.nl), the idea is to develop a method that uses publicly available datasets (eg BAG) and building permit applications in order to create a reference dataset containing all buildings where a vertical extension or a construction on top of an existing building have been conducted. Such a dataset can then be used to give a confidence factor for the feasibility of an extension to an existing building.

**Contact:** [Ken Arroyo Ohori](https://3d.bk.tudelft.nl/ken)
