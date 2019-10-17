# Airbnb anaylsis

The following work has been done to analyse the dataset found at http://data.insideairbnb.com/united-kingdom/england/london/2019-07-10/data/listings.csv.gz

The work has been done using Anaconda using a custom environemnt `yuvoh_conda_env.yml` 

Additional Data has been brought in from the London Datastore: https://data.london.gov.uk/dataset/london-borough-profiles

## 1_Data_Exploration_Pandas_Profile_Raw.ipynb

This notebook uses pandas_profiling to create an automated report into the raw data provided.

## 2_Data_Exploration_Cleaning.ipynb

From analysing the raw data this notebook does cleanup and drops the various data fields.

## 3_Data_Exploration_Pandas_Profile_Clean.ipynb	First Upload	22 minutes ago

This notebook uses pandas_profiling to examine the cleaned data using the code in `2_Data_Exploration_Cleaning.ipynb`

## 4_Feature_Engineering.ipynb	

This notebook created new features from the data to be used for further analysis

## 5_Price_Analysis.ipynb

This notebook examines the listed price and it's distribution for each property in the dataset and uses Ordinary Least Squares to create a regression model

## 6_Borough_Analysis.ipynb

This notebook aggregated the data for each borough and join it to data from the Mayor of London for each borough and creates regression models and geographic plots.

## 7_Data_Modeling.ipynb

This model extends the regression models from `6_Borough_Analysis.ipynb`

## Additional files

These files are produced by pandas_profiling which examines each field in the dataset:
`report_cleaned.html`
`report_raw.html`
