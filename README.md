Title: Predicting Air Quality in NYC Using Traffic Volume and Pollutant Levels

Description: 
Our project aims to find the coorelation between traffic volume and 2 pollutants levels- NO2 and Fine Particles. 
Sourcing the data from NYC Open Data and the Enviornment & Health portal, we used our knowledge of data cleaning and SQL to set up our data to be used. 
We created 3 models to predict future air quality which challenged ourselves to 
(1)examine the coorelation between the pollutant levels and traffic volume and 
(2) see if we were able to predict the future levels based off previous data.
Using various metrics to evaluate our predictions, we found great success in all 3 models.
Under each model you can see visualizations of our predictions compared to the actual values. 

Installation: 
In order to run our project please make sure you have python 3.11.9 for our LSTM model as it uses that version of python to run: https://www.python.org/downloads/release/python-3119/
If you do not have this version of python, issues may occur in running the code and displaying the results.
After installing Python 3.11.9, you'll need to install the libraries we used by running the command pip install numpy matplotlib pandas scikit-learn tensorflow in your terminal. This makes sure your computer has all the tools needed to run the machine learning models and show the graphs properly.
Our code is in Jupyter Notebooks so please make sure to have the 'Jupyter' extension downloaded when viewing in VS Code: https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter 
Our data files our within the data_files folder so there is no need to download external data.

Usage: 
Because our code is in Jupyter Notebook please run each cell at a time in order to follow the process of our project, failure to do so will inhibit future parts to run.
This code and the visualizations that come with it help us view how traffic volume and pollutants are related. 
It allows us to look into how we can use data science to explore issues pertaining to cities and emphasize enviornmental concerns.  
While we focused specifically on NYC and 2 pollutants, this can be expanded to other cities and other pollutants if the data is available.  

Table of Contents: 
data_files folder: Where we store the data files used.
processed_data: Where we store the data we processed and cleaned. 
gitattributes: How we were able to export the raw data
python-version: 3.14 for everything besdies the LSTM which is 3.11.9
01_data_cleaning: The first process for cleaning the data
02_analysis_and_modeling: The second part of the data cleaning after exploring our specific desires and our code for our 3 models with visualizations for all
main: A hi from us :)
pyproject: The set up for our necessary files 
sratch: Using pandas
uv: Used to sync our data 
