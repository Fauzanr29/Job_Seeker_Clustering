# ✨ Job Seekers : Clustering With K-Means ✨ 
This data relates to job seekers who want to look for work in each region, especially this data in the Pandeglang - Banten area in Indonesia. With the aim of clustering based on education and age variables using K-Means clustering
![python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Microsoft PowerPoint](https://img.shields.io/badge/Microsoft_PowerPoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white)

If you don't know yet, the .ipynb file contains the code and explanation, which you can also see easily, unfortunately the explanation is still in Indonesian and has not been translated into English (https://github.com/Fauzanr29/Job_Seeker_Clustering/blob/main/Job_Seeker_Clustering.ipynb)


## Objectives

These job seekers register to look for work by registering themselves with the Manpower and Transmigration Service Agency in each region in Indonesia. This is done on the basis of pre-requisites to fulfill the completeness of work registration to work in a company or work registration as a foreign worker in other countries. This is done by the government to collect data in each region to observe the number of registered job seekers, so that in each region of Indonesia we can find out how much unemployment there is by comparing the population size in each region.

**Business Objective**
This clustering was carried out to see the relationship between education and age in job seekers.
From this data, it can also be seen what the trend of job seeker registration is each month and each year. how many registrants are in each region. what final level of education has the most registrations. and what is the average age of registrants

## Libraries
Libraries such as [pandas](https://pandas.pydata.org/), [NumPy](https://numpy.org/), [matplotlib](https://matplotlib.org/), and [seaborn](https://seaborn.pydata.org/) are the most commonly used in the analysis. However, I also used [sklearn](https://scikit-learn.org/stable/), [plotly](https://chart-studio.plotly.com/~konzania#/) to perform interactive visualization
```python

import pandas as pd
import numpy as np

import seaborn as sns
import matplotlib.pyplot as plt

import plotly.express as px
from chart_studio import plotly
import chart_studio.plotly as py

#import plotly.plotly as py
import plotly.offline as pyo
import plotly.graph_objs as go

import warnings
warnings.filterwarnings('ignore')
```

## Result Preview

1) age range of applicants who make a yellow card to look for work:
17 - 25 years, where the age range of 16-18 is the average age
Their final education was at SMA/SMK/MA, while the average person aged 19-25 went to college or looked for work.

2) The highest education that makes a yellow card for looking for work is 1) Vocational School, 2) High School, 3) MA
where in the case of final vocational education,
where vocational schools are indeed prepared after graduation to immediately work

3) The Top 10 Registrant Districts that have made yellow cards are:
  1) Labuan, 2) Pandeglang, 3) Cadasari, 4) Karang Tanjung, 5) Maja Sari
  6)Menes, 7)Saketi, 8)Pulosari, 9)Cikedal, 10)Kaduhejo
