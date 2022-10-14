---
layout: benchmark
title: Buildings CityGML
permalink: /projects/geobim-benchmark/buildingslod3.html
---

<h1>CityGML Buildings in LoD 3</h1>

<div class="row">
  <div class="col-sm-12 col-xs-12"><img class="img-responsive" src="{{ "/projects/geobim-benchmark/img/BuildingsLOD3-1.gif" }}" style="max-height: 500px"></div>
</div>

<div class="row">
  <div class="col-sm-12 col-xs-12"><img class="img-responsive" src="{{ "/projects/geobim-benchmark/img/BuildingsLOD3-2.gif" }}" style="max-height: 500px"></div>
</div>

- - -

* Table of Content
{:toc}

- - -

## Short description

Procedurally generated CityGML building models (with the software <a href="http://filip.biljecki.com/code/Random3Dcity.html">Random3Dcity</a>)

Only buildings are included, and they are represented in Levels of Detail (LoD) 3, therefore including roof shapes, windows, doors. Please check the CityGML description on the linked website and related documentation to have more details on usage and licence.

The file was further checked, validated and improved through '3DcityDB' and 'Safe Software FME' Validation tools, manual editing and processing through FME tools.

**An improved and corrected version is published on 11th June 2019.** Please, download and use this new version (at the end of this page).

## Technical details

Name of the file: <strong>BuildingsLOD3.gml</strong>

Used CityGML version:<strong>2</strong>

Level(s) of Detail: <strong>LoD 3</strong> (in the same GML file)

The geometries are all managed as<strong> MultiSurfaces.</strong>


## Georeferencing details

Coordinate reference system:<strong> EPSG: 28992 – Amersfoort / RD New</strong>

Bounding box coordinates:

<div class="row">
  <div class="col-sm-12 col-xs-12"><img class="img-responsive" src="{{ "/projects/geobim-benchmark/img/BuildingsSRSdetails.gif" }}" style="max-height: 500px"></div>
</div>

Model orientations:

<div class="row">
  <div class="col-sm-12 col-xs-12"><img class="img-responsive" src="{{ "/projects/geobim-benchmark/img/BuildingsOrientation.gif" }}" style="max-height: 500px"></div>
</div>

In the following Figure, you can read some dimensions of the model, to be used for the tests in Task 3.

<div class="row">
	<img class="img-responsive" src="{{ "/projects/geobim-benchmark/img/BuildingsLOD3-Fig1.gif" }}" title="Sample of dimensions of the CityGML buildings, read by the software FZK (in red, the points and lines marking the measured distances)." >
</div>

## Semantics details

Here, the entities included in the model are listed model (you can read the CityGML documentation for their full description):

* core:CityModel
* bldg:Buildings
* bldg:BuildingInstallation
* bldg:Door
* bldg:GroundSurface
* bldg:OuterFloorSurface
* bldg:RoofSurface
* bldg:WallSurface
* bldg.:Window


### 6 Elements

In the following images and video you can see the model (in the software Azul), with the classification (and hierarchies) of objects and <strong> attributes</strong>  of specific elements, to be used as reference while performing the Task 3.
From these views you can also have a view about how the geometry looks like, in order to have a visual reference for testing your software.


<strong> Element 1</strong>
<div class="row">
	<img class="img-responsive" src="{{ "/projects/geobim-benchmark/img/BuildingsLOD3-Fig2.gif" }}" title="Element 1	(in yellow)." >
</div>
------------
<strong> Element 2 </strong>
<div class="row">
	<img class="img-responsive" src="{{ "/projects/geobim-benchmark/img/BuildingsLOD3-Fig3.gif" }}" title="Element 2	(in yellow)." >
</div>
------------
<strong> Element 3</strong>
<div class="row">
	<img class="img-responsive" src="{{ "/projects/geobim-benchmark/img/BuildingsLOD3-Fig4.gif" }}" title="Element 3	(in yellow)" >
</div>
-----------------
<strong> Element 4</strong>
<div class="row">
	<img class="img-responsive" src="{{ "/projects/geobim-benchmark/img/BuildingsLOD3-Fig5.gif" }}" title="Element 4	 (in yellow)." >
</div>
------------
<strong> Element 5</strong>
<div class="row">
	<img class="img-responsive" src="{{ "/projects/geobim-benchmark/img/BuildingsLOD3-Fig6.gif" }}" title="Element 5	 (in yellow)." >
</div>
------------
<strong> Element 6</strong>
<div class="row">
	<img class="img-responsive" src="{{ "/projects/geobim-benchmark/img/BuildingsLOD3-Fig7.gif" }}" title="Element 6 (in yellow)" >
</div>

---------------

### Video of the CityGML Buildings in LoD 3

<iframe width="560" height="315" src="https://www.youtube.com/embed/1Z0Fh2ATXkY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

--------------------------
## Download

You can download the BuildingsLOD3.gml data (corrected version 11/06/2019) from this [**link**](https://zenodo.org/record/7186279#.Y0frMC8Rq7c)
 - - -
