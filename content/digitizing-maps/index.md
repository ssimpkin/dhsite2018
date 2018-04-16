---
title: "Digitizing maps"
weight: 50
---

## Overview

In QGIS, we’ll trace polygons to represent the buildings from the fire insurance plans and add additional attribute information to them in order to enrich our dataset.

## Creating a new shapefile

We’ll have to create a blank shapefile and set the appropriate coordinate system. In this case, we’ll set the coordinate system to the same one that we’ve been using thus far, epsg:2951.

While creating the new shapefile, we’ll include several fields so that we collect different bits of information for each polygon. 

Once the fields have been added, we’ll save the shapefile.

## Tracing polygons

Now that we have our shapefile created with our fields, we’ll start tracing our polygons. 

1. Click on the toggle edit tool (pencil) to start the editing. 

2. Click on the add feature tool to start creating the polygon.

3. Use the left click button to begin tracing the polygon and to create the nodes for the polygon. When you’re done tracing the polygon, do a right click. 

4. Insert the attribute information for the fields and click ok once complete

Repeat the steps for each polygon feature that you want to add.

## Saving the feature

To save the feature, click on the toggle edit tool and select save. You may want to do this after adding several polygons.