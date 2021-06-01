# NYCTAXI-ANALYSIS
Bu proje New York Taksi verilerinin 2017 yılındaki kapsamlı analizini ele almaktadır.


In this document, I will walk through the analysis of New York City Taxi Data (with download link shown in Section II) using Python. 6 months of “Yellow” label data will be loaded and analyzed.


#The following libraries are the basic libraries for data analytics.

import pandas as pd
import numpy as np
import urllib.request
import zipfile
import random
import itertools
import math

import shapefile
from shapely.geometry import Polygon
from descartes.patch import PolygonPatch
import matplotlib as mpl
import matplotlib.pyplot as plt
plt.style.use('ggplot')
%matplotlib inline

##Furthermore, to deal with the large scale of data (4GB for 6 months in this case), a database is needed. 
##Here I will use SQLAlchemy, which is a Python SQL toolkit and Object Relational Mapper that gives application developers the full power and flexibility of SQL.


![alt text] (https://github.com/uyducusirinn/NYCTAXI-ANALYSIS/blob/main/IMG/location.JPG)




