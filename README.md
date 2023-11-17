# Aviation Safety

## Business Understanding

## Data Understanding

Our data come from the Kaggle [Aviation Accident Database & Synopses](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses/), which is itself pulled from the National Transportation Safety Board (NTSB). The data, with a handful of exceptions, begin in 1982 and go up to 2022. We start with 88,889 entries, with 31 different columns of data:

![Alt text](images/initial_data_info.png)

Before diving too far into the data, it is important to emphasize what we do *not* have. **The most important limitation is that we don't have information on flights for which there is no incident report** -- which is filed when something goes wrong with the plane. We don't have the denominator of total flights during this period. Instead, we only have flights for which an incident report was filed.  

## Data Preparation

We did our data cleaning in `notebooks/data_cleaning.ipynb`, after which we exported a cleaned version of the data to `data/AviationData_cleaned.csv`. Here, we'll recap exactly what we did to clean the data.

## Data Analysis & Visualization

