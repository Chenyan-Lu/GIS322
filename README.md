# ASU-GIS-322
This repository contains the learning materials for GIS 322: Programming Principals II.
Designed by Ziqi Li (liziqi1992@gmail.com) and Wenwen Li (wenwen@asu.edu), improved by Yuanyuan Tian (ytian72@asu.edu), School of Geographical Sciences and Urban Planning, Arizona State University.

# Outline

Module 0: Welcome and Start Here
* Set up Your Programming Environment - Introduction to Google Colaboratory

Module 1: Review of Python Basics
* Data Types, Functions and Modules
* Conditions and Loop
* Review of Numpy for Basic Usage and File Read

Module 2: Spatial Features and Data Structure
* Vector Part 1
* Vector Part 2

Module 3: Geometry operations using Shapely
* Geometry Collection in Shapely
* Spatial Relationship
* Matplotlib Display Shapely Object

Module 4: Managing GIS Data in Python
* Reading and Writing Spatial Data
* Map Projections
* Creating a GeoDataFrame from Coordinates

Module 5 Geospatial Operations and Geoprocessing
* Geometric Operations
* Table Join and Spatial Join
* Geocoding

Module 6 - Advanced Geovisualization in Python
* Interactive Mapping with Bokeh
* Adding a Web Basemap using Folium

Module 7
* Final project



# How to modify GitHub Repository and Canvas of GIS 322

(1) Make repository changes.

(2) How to change the hyperlink of the “Open in Colab” button: 


<img width="180" alt="image" src="https://github.com/ASUcicilab/GIS322/assets/43053656/7ab0aac9-7ef0-4895-be1f-8aa32d2cecf9">


Open a notebook (e.g, [https://github.com/Yuanyuan-T/ASU-GIS-322-Summer-2021/blob/master/notebooks/5_3_Geocoding.ipynb](https://github.com/ASUcicilab/GIS322/blob/main/notebook/Module_1_(1)_Data_Types_Functions_and_Modules.ipynb)), click "edit this file", find the below code block, change the notebook link following the syntax as 

"https://colab.research.google.com/github/ASUcicilab/GIS322/blob/main/notebook/Module_1_(1)_Data_Types_Functions_and_Modules.ipynb". 


```
{"cell_type":"markdown","metadata":{"id":"view-in-github"},"source":["<a href=\"https://colab.research.google.com/github/ASUcicilab/GIS322/blob/main/notebook/Module_1_(1)_Data_Types_Functions_and_Modules.ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"]}
```


(3) Get the rendered page:
Copy the name of the GitHub repository (https://github.com/ASUcicilab/GIS322) in https://nbviewer.jupyter.org/.

You will get a rendered repo: https://nbviewer.org/github/ASUcicilab/GIS322/tree/main/notebook/

*Notice that nbviewer has caching issue, it won’t change in time if you make changes on GitHub after you render any page in your repository. So the best practice is to ensure everything in the repo is good to go, then render this repo. One walkaround is to rename your repo, and render it again. 

(4) Go to Canvas, change the link to the rendered GitHub page:
Click "Edit", shift to html editor:
<img width="1202" alt="image" src="https://github.com/ASUcicilab/GIS322/assets/43053656/178c2eb2-5706-4bd0-9e34-c3a98389c768">

Update the link using nbviewer.
<img width="800" alt="Raw HTML Editor" src="https://user-images.githubusercontent.com/43053656/125877494-ad993e99-c530-4c4e-96be-c9e9675b1348.png">

