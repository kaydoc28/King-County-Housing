# King-County-Housing
This is an analysis project conducted in Python as part of the Career Foundry Data Immersion Program.
## Motivation
King County is the most populated county within the Washington State and the 14th  most populated county in the United Sates making this a prime real estate destination.
## Objective
Exploratory analysis of the physical variables (such as bathrooms, bedrooms, floors, etc.) that impact price. This analysis is geared to better educate real estate agents in order to help them find their clients' dream home. 
## Data
“House Sales in King County USA ”, Accessed from https://www.kaggle.com/datasets/harlfoxem/housesalesprediction 
## Data Limitations
Data is from years 2014 and 2015 which will not provide the most up to date information.
## Cleaning Procedures
  - Several Columns that contained information that was not needed for this analysis (sqft-living15, sqft_above, etc.)
  - 177 duplicates were found and removed
  - One outlier contained a value of 33 bedrooms. An average of 3 was imputed. 
  - No sensitive or personal data was present in the dataset. 
 ## Research Questions
  - How does renovation year impact the price?
  - Does the geographical location of the estate impact the price?
  - What is the average sqft of houses within King County?
  - Does the year built impact the price in a negative/ positive way?
  - What properties include waterfront/ View?
  - Are certain zip codes pricier than others?
  ## Tools
This analysis used Excel and Python. The following libraries were used in Python 
  - Panda
  - Numpy
  - Seaborn
  - Matplotlib
  - Scipy
  - Quandl
  - Pylab
  - SKlearn
  ## Tableau Project
  This presentaion is available on [Tableau](https://public.tableau.com/app/profile/kayleigh.a.dougherty/viz/KingCountyStoryboard/KingCounty?publish=yes).
  The Tableau dashboard includes... 
   - An overview of King County
   - Exploratory Analysis
   - Correlation Analysis
   - Regression Analysis
   - Cluster Analysis
   - Geospatial Analysis
   - Insights
