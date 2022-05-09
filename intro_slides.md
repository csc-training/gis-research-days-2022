--- 
title: Geoportti computing services for geospatial research at CSC 
subtitle: – potential and challenges
author: Jesse Harrison and Samantha Wittke
date: 10.05.22
lang: en
theme: csc-2019
---

# Practicalities

* who is this workshop for?
* please interrupt ask lots of questions
* shared notes on HackMD

# HackMD

<br></br>
[`hackmd.io/@GeospatialCSC/GISRD`](https://hackmd.io/@GeospatialCSC/GISRD/edit)
<br></br>

# Today

* Short intro to CSC and available resources
* Group work and discussion time

# Geoportti

* open research infrastructure in Finland 
* science support with access to geospatial data and high performance and cloud computing resources
* promotion of the use of geospatial data and geoinformatics methods in research and university education
* [https://www.geoportti.fi/](https://www.geoportti.fi/)

# CSC

<p align="center">
  <img src="./img/csc-bg.png">
</p>

# CSC services

[`research.csc.fi/en/service-catalog`](https://research.csc.fi/en/service-catalog)

<br></br>
<div class="column">
**Compute & Analyze**

  - cPouta / ePouta
  - Puhti / Mahti / LUMI
  - Notebooks
  - Rahti

</div>
<div class="column">
**Store, Share & Publish Data**

  * Allas
  * Fairdata
  * Paituli
  * (EUDAT)
</div>

* Sensitive Data services

-> **free** for open science at Finnish university and state research institute users

# Why use CSC resources?

When own computer is not enough:

* Resource needs (time (> 2 hours), memory (> 8 GB), storage (> 50GB))
* preinstalled software
* data available

**-> Outsource computations, keep own computer free**

# CSC expertise

<div class="column">
...at your fingertips:

[`docs.csc.fi`](https://docs.csc.fi)

[`research.csc.fi`](https://research.csc.fi)

</div>
<div class="column">
**\+ servicedesk@csc.fi**
<br></br>

* Geoinformatics team
* AI and data analytics team
* Storage team
* Supercomputer team
* Cloudcomputing team
* Accounts team
* ...
</div>

# How we can help

<div class="column">
* 'Z is not working as expected'
* 'my code gives error Y '
* 'can A be installed to Puhti?'
* 'any advice how to do X?'
* training/example wishes

**-> servicedesk@csc.fi**

[Speed up your request](https://docs.csc.fi/support/support-howto/)

</div>
<div class="column">
* Setting up pipelines, product provision, R&D, ...

**-> CSC as project partner / subcontractor**
</div>

# Key to geocomputing - Puhti 

![](img/gui_to_script.png)

# Computing solutions - Puhti

<p align="center">
  <img src="img/puhti_overview.png" width="50%"> 
</p>

# Puhti webinterface 

-> check your data, testing something, code development

<br></br>
[`puhti.csc.fi`](https://puhti.csc.fi)
<br></br>

# Software

<div class="column">
* FORCE & SPLITS
* GDAL / OGR
* LasTools 
* MatLab / Octave
* Mapnik
* OpenDroneMap
* Orfeo Toolbox
* PCL
</div>
<div class="column">
* PDAL
* CloudCompare
* QGIS
* SagaGIS
* SNAP, Sen2cor
* WhiteboxTools
* Zonation
* ...
</div>

# Python

Geoconda
* about 600 packages
* for raster, vector, pointcloud processing
* + scikit and other data science packages

other modules:
* keras, pytorch
  * have geopandas, rasterio

You can also create own environment/ install own software!

# R environment on Puhti

- Includes: 
   - R and RStudio Server
   - 1300+ R packages
   - Pre-installed libraries / software required by R packages
   - Mathematics library for faster calculations (Intel® OneMKL)
   - TensorFlow (for using [the R Interface to Tensorflow](https://tensorflow.rstudio.com/))

# R environment on Puhti

<p align="center">
  <img src="./img/r-access.svg">
</p>


# Potential

* speedup computations
* large computations
* more GPU power (for ML)
* outsource computations
* avoid software installation issues
* recipe for environment provided
* CSC expertise
* ...

# Challenges

* Linux and commandline
* get to know new system and concepts
* possibly new software/ways of working
* data transfer bottleneck
* ...

# Usecases

* large pointcloud/raster/vector processing and analyses
  * processing all forest areas of Finland for forest disturbance management
  * large DEM analyses
* Machine learning with huge geospatial datasets

* yours?


# Getting started

Check out our [Geocomputing page](https://research.csc.fi/geocomputing)

* [Step by step instructions ](https://research.csc.fi/en/accounts-and-projects)
* [Find your account and project information](my.csc.fi)

* [Read the docs](https://docs.csc.fi)

* check our [tutorials](https://docs.csc.fi/support/tutorials/) and [geocomputing examples](https://github.com/csc-training/geocomputing)


# Training

* ['Using CSC environment efficiently' self-learning course](https://csc-training.github.io/csc-env-eff/)
* [16.05: Hybrid Earth Observation workshop](https://ssl.eventilla.com/event/zArJA)
* [18.05: Webinar - CSC´s generic services for storing, sharing and publishing data](https://ssl.eventilla.com/event/pEAl3)
* [09.-10.06: Fundamentals of Machine Learning](https://ssl.eventilla.com/mlfundamentals)


* [CSC geoinformatics training material](https://research.csc.fi/gis-learning-materials)

-> follow our [training calendar](https://www.csc.fi/en/training#training-calendar)

# Groupwork

# By yourself

Think about your own use case / possible future use case / idea:

* What are your requirements? Memory, storage, time,..
* What software do you need? Any restrictions?
* What is your workflow? Can it be more efficient by using other tools/coding? 
* What are steps that could be parallelized? In what way?
* Expected bottleneck

# In group 

* Potential for own or future use case?
    * What do you think you can achieve when using CSC resources
    * Could you do something that is not possible without CSC resources
    * 
* Challenges and how to overcome
* Any questions?

# Present

* collect in HackMD
* short presentation

