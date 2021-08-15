# MAST30034 Project 1 - Quantitative Analysis
- Student Name: Ziqian Wu
- Student ID: 1067683
- Due Date: Friday 16th of August 11:59:00 am (AEST).
- Report Link: https://www.overleaf.com/read/nkmsqwhckqyn

# Dependencies
- Language: Python 3.8.5 and R 4.1106
- Packages: pandas,os,urllib,numpy,seaborn,matplotlib,folium,warnings,bokeh
- library: dataPreparation,fitdistrplus,speedglm,performance,cvms,broom,tibble,
            dplyr,sf,curl,tmap,tmaptools



# Datasets
- NYC TLC: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page
- 2015 Jan, Feb and Mar New York weather data: https://www.ncei.noaa.gov/orders/cdo/2680310.csv
- 2016 Jan New York weather data: https://www.ncei.noaa.gov/orders/cdo/2684218.csv


# Directory
_Change this to fit your needs when you have started the project._
- `raw_data`: Contains all the raw data files.  
- `preprocessed_data`: Contains all the preprocessed data files. 
- `plots`: Output and save all your figures here.
- `code`: Keep all notebooks and scripts in this folder. Running the notebooks 
    from start to end:
    - downfile.ipynb for "Extracting Data" from the website and store them in "raw_data".
    - Yellow taxi preprocessed data.ipynb :"Preprocessing" and "Exploratory Data Analysis" 
    for the yellow taxi data
    - Green taxi preprocessed data.ipynb : "Preprocessing" and "Exploratory Data Analysis" 
    for the green taxi data
    - Yellow taxi data visualisation.ipynb : "Analysis and Visualisation" for the 
    yellow taxi data.
    - Green taxi data visualisation.ipynb : "Analysis and Visualisation" for the 
    green taxi data.
    - Yellow taxi data prediction.ipynb : merge yellow taxi data and weather data
    and do some data engineering. Prepare for "Statistical Modelling"
-  Aftering running all the notebooks, run `Project 1 prediction.Rmd` to fit a 
statistical model to predict future data. 
