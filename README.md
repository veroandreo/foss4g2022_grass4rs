# [GRASS GIS for remote sensing data processing and analysis ](https://talks.osgeo.org/foss4g-2022-workshops/talk/NCMHSM/)

This repo holds the Jupyter notebook that will be used for the **GRASS for Remote sensing**
workshop at FOSS4G 2022 in Florence.

We will present and exemplify a subset of GRASS GIS toolsets for satellite imagery
data processing and analysis in combination with other core modules and add-ons in
a workflow going from data download to supervised classification of different scenes
and visualization of results.

We will start with some basic GRASS concepts, but we'll assume Python and remote
sensing basic knowledge. Furthermore, **participants should install the needed
software and download the data in advance**.

## Software

### GRASS GIS

We will use **GRASS GIS 8.2+**. It can be installed either through standalone
installers/binaries or through [OSGeo-Live](https://live.osgeo.org/en/index.html)
(a linux based virtual machine which includes all OSGeo software and packages).

##### MS Windows

There are two different options:
1. [Standalone installer 64-bit](https://grass.osgeo.org/grass82/binary/mswindows/native/WinGRASS-8.2.0-1-Setup.exe)
2. [OSGeo4W 64-bit](http://download.osgeo.org/osgeo4w/v2/osgeo4w-setup.exe)

For Windows users, **we strongly recommend installing GRASS GIS through the OSGeo4W package** (second option),
since it allows to install all OSGeo software.

##### Ubuntu Linux

Install GRASS GIS 8.2 from the "unstable" package repository:

```
sudo add-apt-repository ppa:ubuntugis/ubuntugis-unstable
sudo apt-get update
sudo apt-get install grass grass-gui grass-dev
```

##### Fedora, openSuSe Linux

For other Linux distributions including **Fedora** and **openSuSe**,
simply install GRASS GIS with the respective package manager.
See also [here](https://grass.osgeo.org/download/)

##### Mac OS

Have a look at: http://grassmac.wikidot.com/downloads

## Other software

- sentinelsat
- jupyter
- folium
- scikit-learn
- pandas
- numpy
- seaborn
- matplotlib

## Data

- NC sample data: https://grass.osgeo.org/sampledata/north_carolina/nc_spm_08_grass7.zip
- Sentinel 2 scenes: https://www.gisnet.lv/~marisn/GRASS_workshop/
- OSM land use:

## Lecturers

- [Veronica Andreo](https://veroandreo.gitlab.io/) holds a PhD in Biology and an MSc in Remote Sensing and GIS Applications. She is a researcher for CONICET working at the Argentinian Space Agency. Her main interests are remote sensing and GIS tools for disease ecology research and applications. She is part of the GRASS Dev Team, currently serving as PSC chair.
- Markus Neteler, PhD, is a cofounder of mundialis after having spent 15 years as a researcher in Italy. His focus is on Earth Observation, GIS and cloud computing. Markus managed for two decades the GRASS GIS project, and he is a founding member of OSGeo and other organizations.
- Māris Nartišs is a geographer with more than ten years of experience in teaching topics related to GIS, remote sensing and geomorphology. A free software supporter, GRASS GIS contributor.
