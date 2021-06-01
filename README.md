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




