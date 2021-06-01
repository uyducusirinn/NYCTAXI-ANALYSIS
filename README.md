# NYCTAXI-ANALYSIS
Bu proje New York Taksi verilerinin 2017 yılındaki kapsamlı analizini ele almaktadır.


In this document, I will walk through the analysis of New York City Taxi Data (with download link shown in Section II) using Python. 6 months of “Yellow” label data will be loaded and analyzed.


# The following libraries are the basic libraries for data analytics.

import pandas as pd </br>
import numpy as np  </br>
import urllib.request </br>
import zipfile </br>
import random </br>
import itertools </br>
import math </br>

import shapefile </br>
from shapely.geometry import Polygon </br>
from descartes.patch import PolygonPatch </br>
import matplotlib as mpl </br>
import matplotlib.pyplot as plt </br>
plt.style.use('ggplot') </br>
%matplotlib inline </br>

## Furthermore, to deal with the large scale of data (4GB for 6 months in this case), a database is needed. 
## Here I will use SQLAlchemy, which is a Python SQL toolkit and Object Relational Mapper that gives application developers the full power and flexibility of SQL.


![location](https://user-images.githubusercontent.com/44877995/120295466-d1465b80-c2cf-11eb-8e67-d2f5f6ba2d47.JPG)



# Q1: Which regions have most pickups and drop-offs?

![popular_zones](https://user-images.githubusercontent.com/44877995/120296520-e1ab0600-c2d0-11eb-80d8-d4ffc6f9758d.JPG)
![brgh](https://user-images.githubusercontent.com/44877995/120296609-f7203000-c2d0-11eb-91fb-a35e55de4d30.JPG)


# Q2: When are the peak hours and off-peak hours for taking taxi?

![graphics](https://user-images.githubusercontent.com/44877995/120296741-17e88580-c2d1-11eb-802e-9f1e9ff8d87c.JPG)


# Q3: What are the differences between short and long distance trips of taking taxi?


![trips_analysis_graphic](https://user-images.githubusercontent.com/44877995/120296859-38184480-c2d1-11eb-874a-b8d58540b90d.JPG)



![zones](https://user-images.githubusercontent.com/44877995/120296964-52522280-c2d1-11eb-9490-5fc9d3057ce8.JPG)












