# Hands-on Practice Lab: Data Wrangling

<p align="center">
  <a href="https://skills.network" target="_blank">
    <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/assets/logos/SN_web_lightmode.png" width="300" alt="Skills Network Logo">
  </a>
</p>

---

## Estimated Time Needed  
**30 minutes**

---

## Lab Overview

In this lab, you will use the skills acquired to:

- Handle missing data in different ways  
- Correct the data types of DataFrame attributes as required  
- Standardize and normalize specific dataset attributes  
- Visualize data as grouped bar graphs using binning  
- Convert categorical data into numerical indicator variables

---

## Setup

This lab uses the following libraries:

- `skillsnetwork` (to download the dataset)  
- [`pandas`](https://pandas.pydata.org/) for data manipulation  
- [`numpy`](https://numpy.org/) for mathematical operations  
- [`matplotlib`](https://matplotlib.org/) for plotting  

---

## Importing Required Libraries

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
%matplotlib inline

