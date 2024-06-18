# House Price Prediction based on Crime and Education Data

This project aims to predict house prices using crime and education data. We utilize data retrieved from the FBI API for crime statistics, perform geocoding to convert latitude and longitude to zip codes, and integrate this data with existing education and house data.

## Steps Involved:

1. **Crime Data Retrieval and CSV Saving**:
   - Utilized FBI API to fetch crime data.
   - Saved the retrieved data into a CSV file (`crime_data.csv`).

2. **Geocoding for Zip Code Addition**:
   - Converted latitude and longitude data to zip codes using geocoding techniques.
   - Added a `zipcode` column to the crime data CSV.

3. **Data Cleaning and Preparation**:
   - Cleaned education and house data CSV files (`education_data.csv`, `house_data.csv`).
   - Merged cleaned data with the crime data based on zip codes.

4. **Machine Learning Model Training**:
   - Initially attempted Linear Regression but found it ineffective.
   - Applied RandomForestRegressor for house price prediction.

## Files Included:
- `arrests_data.csv`: Contains crime statistics fetched from FBI API.
- `education_data.csv`: Existing education data.
- `house_data.csv`: Existing house price data.

## Technology:
- python
- numpy
- pandas
- arcgis
- Sklearn
- Matplotlib
- Api
- seaborn

  
## Camp Summary :
# Arctic-Summer-Camp-2024
### Day 1 
- 9.00 AM – 9.30 AM: Introduction & Logistic 
- 9.30 AM – 10.10 AM: Python basis
- 10.15 AM – 11.00 AM: Solution to linear Systems using numerical methods.
- 11.00 AM – noon: Lunch
- Noon – 12.40 PM : Python library (Numpy)
- 12.45 PM – 1.00 PM: Project introduction : Predict House Prices based on crime and education data
- 1.00 PM – 3.00 PM Project Hands on time : got crime data using fbi api 
- 3.00 PM – 3.15 PM Break
- 3.15 PM – 4.30 PM Project Hands on time : saved data in csv file
- 4.30 PM – 5.15 PM Team Project presentation and discussion (15 min per team) 
- 5.15 PM – 5.30 PM Closing remarks and Q&A

### Day 2 
- 9.00 AM – 9.30 AM: Previous day review and Q&A 
- 9.30 AM – 10.10 AM: Python library (Pandas)
- 10.15 AM – 11.00 AM: Numerical Solution to Ordinary Differential Equations.
- 11.00 AM – noon: Lunch
- Noon – 1.00 PM: Data Preprocessing techniques 
- 1.00 PM – 3.00 PM: Project Hands on time  : geo coding
- 3.00 PM – 3.15 PM: Break
- 3.15 PM – 4.30 PM: Project Hands on time : data cleaning using pandas
- 4.30 PM – 5.15 PM: Team Project presentation and discussion (15 min per team) 
- 5.15 PM – 5.30 PM: Closing remarks and Q&A


### Day 3 
- 9.00 AM – 9.30 AM: Previous day review and Q&A 
- 9.30 AM – 10.10 AM: Python library (Matplotlib)
- 10.15 AM – 11.00 AM: Transformations using matrix algebra. 
- 11.00 AM – noon: Lunch
- Noon – 1.00 PM: Introduction to Machine learning 
- 1.00 PM – 3.00 PM Project Hands on time : data visualization using matplitib
- 3.00 PM – 3.15 PM Break
- 3.15 PM – 4.30 PM Project Hands on time 
- 4.30 PM – 5.15 PM Team Project presentation and discussion (15 min per team) 
- 5.15 PM – 5.30 PM Closing remarks and Q&A

### Day 4 
- 9.00 AM – 9.30 AM: Previous day review and Q&A 
- 9.30 AM – 10.10 AM: Introduction to C 
- 10.15 AM – 10.25 AM: Introduction to Computer Hardware
- 10.25 AM - 10.45 AM: Introduction to Parallel Programming
- 11.00 AM – noon: Lunch
- Noon – 1.00 PM: Advanced topics in Deep learning   
- 12.45 PM – 1.00 PM: Project introduction 
- 1.00 PM – 3.00 PM Project Hands on time : train model, linear regression
- 3.00 PM – 3.15 PM Break
- 3.15 PM – 4.30 PM Project Hands on time : data modeling
- 4.30 PM – 5.15 PM Team Project presentation and discussion (15 min per team) 
- 5.15 PM – 5.30 PM Closing remarks and Q&A


### Day 5 
- 9.00 AM – 9.30 AM: Previous day review and Q&A 
- 9.30 AM – 10.10 AM: Introduction to Computer Hardware
- 10.15 AM – 11.00 AM: Introduction to Parallel programming  
- 11.00 AM – noon: Lunch
- Noon – 1.00 PM: Writing a parallel program using Open MP  
- 1.00 PM – 3.00 PM Project Hands on time : created powerpoint slides
- 3.00 PM – 3.15 PM Break
- 3.15 PM – 4.30 PM Project Hands on time : review what we did past 4 days 
- 4.30 PM – 5.15 PM Final Presentation(15 min per team) 
- 5.15 PM – 5.30 PM Closing remarks and Q&A


