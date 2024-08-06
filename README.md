# Analyzing Food Insecurity in NYC using Safegraph CBG Data 

The aim of this notebook is to investigate the issue of food insecurity by assessing the distances individuals traveled to grocery stores within different census block groups (CBGs), utilizing SafeGraph data. Specifically, we will calculate the average distance traveled to designated grocery stores for each CBG during the following timeframes: March 2019, October 2019, March 2020, and October 2020. This selection of months aims to minimize seasonal variability and the influence of tourism and holiday shopping.

The analysis will be conducted using Apache Spark in conjunction with Google Colab and Google Cloud Dataproc, focusing on distances measured in the NAD83 plane (EPSG:2263).
