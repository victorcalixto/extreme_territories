---
layout: post
date:   2020-03-15
image: "/extreme_territories/images/tutorial1_tumb.png"
title:  "How to import a shapefile into Grasshopper using Urbano"
author: "Victor Calixto"
---

In this tutorial we are going to explore how to import vector and features data from a shapefile into a Grasshopper definition using [Urbano](https://www.food4rhino.com/app/urbano) plugin. We assume that you already have installed [Rhino 6](https://www.rhino3d.com/download) as well as completed Rhino and Grasshopper online tranning from the Assigment 3A from [Archistar Academy](https://academy.archistar.ai/) on Rhino and Grasshopper Essentials.
Therefore, this tutorial is divided in three parts:

+ Installing software dependencies 
+ Preparing the shapefile in QGIS
+ Import the shapefile into Grasshopper

### 1 Installing software dependencies for this tutorial

This tutorial uses three plugins:

* *[Urbano](https://www.food4rhino.com/app/urbano)* which is a Urban Design Grasshopper plugin that for mobility and utilisation analisys of amenities, streets, and public spaces. Also, we can use it to import shapefiles into our Grasshopper definition.

* *[Bifocals](https://www.food4rhino.com/app/bifocals)* it will be used to display at the same time names and icons of components on the Grasshopper canvas. It is a great resource for who are starting to use Grasshopper.

* *[Legend_Settings]* it is a grasshopper cluster built for this discipline to provide settings parameters for a legend based on `Gradient` component.

#### 1.1 Installing Urbano and Bifocals

To install *Urbano* go to [`https://www.food4rhino.com/app/urbano`](https://www.food4rhino.com/app/urbano) and register on the site to have access to the download files. After register and login, download `Urbano v1.0 Installer` and executes the file to install.

Go to [`https://www.food4rhino.com/app/bifocals`](https://www.food4rhino.com/app/bifocals) and download `Bifocals Installer`. Run it to install *Bifocals* plugin.


