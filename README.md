# Satellites Project - Data Science
Data analyze project about satellites and prediction (and more) using machine learning.
## Data Acquisition
Crawling using BeautifulSoup libary to get the information from: https://www.n2yo.com/satellites/?c=&t=country
and adding it into a dataframe.
## Data Cleaning
Going over the information we acquired and handling the data:
- Missing data
- Duplicates
- Outliners
- Convert data of different types
## Visualisation
- Graphic display of the dataset --> make it easier to understand and explain the data
## Machine Learning
* Supervised Learnng:
- Liner Regression - predict satellite's Period by given Perigee (the point where the satellite is closest to Eearth)
- Logistic Regression 1. by Orbit split (low, med, high)  2. by Type split as label 
* Unsupervised Learning:
- K-Means - Clustering the data to check if satellites with different duty have common attributes
