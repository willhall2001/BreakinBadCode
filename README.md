# BreakinBadCode

## Team-Mates:
- William Halloran 
- Alistair Mascarenhas
- James Wagner

## Install 
%pip install requests
%pip install beautifulsoup4
%pip install selenium
%pip install pandas
%pip install geopy
%pip install geopandas
%pip install folium
%pip install openmeteo-requests
%pip install requests-cache
%pip install retry-requests
%pip install numpy
%pip install timezonefinder
%pip install seaborn
%pip install scipy
%pip install matplotlib
%pip install scikit-learn
%pip install statsmodels
%pip install plotly
%pip install sqlite3-binary 

## Structure of Repository
00 GitHub Vivino Flow Chart
- A general flow chart from data pulling, to the final graphs

01 Vivino Web Scraping
- Scrapes all the web data from teh Vivino website and formats it into an SQlite file

02 Popular Wines
- Pulls location information and filters Vivino data into a popular wine dataframe

03 Weather data
- Pulls weather data for the popular wines based on latitude and longitude 

04 Training Dataset
- Pulls vintage data, then merges, formats and filters weather, popular wine and vintage data into a single training dataset

05 ML1 Single Bottle Per District 
- Creates a machine learning model from training dataset one using 1 bottle for certain districts

06 Final Model All Bottles Per District
- Creates a machine learning model for training dataset two using every bottle for certain districts

07 ML3 Single Bottle Different District
- Creates a machine learning model for training dataset three using 1 bottle for different districts

08 Graph Creation
- Creates visualization graphs, showing trends and relationships between wine features

09 Popular Bottle Data
- Filters, pulls weather data for specific popular bottles

10 Best Value and Stats 
- Presents the best valued wines based on key characteristics

All the raw data can be accessed in the "Final_DataFrames" folder 
- This folder containes each chunk of raw data used throughout the code blocks 

Each of the machine learing models can be run with no issue
- Processing time is low, so "Run All" can be used on each of the "Machine_Learning_Model" files

## Attribution Table: 
James Wagner
- Code Section 01, 08 and 10

William Halloran 
- Code sections 02, 03, 04, 05, 06, 07, and 09

Alistair Mascarenhas
- Code section 04, and 08