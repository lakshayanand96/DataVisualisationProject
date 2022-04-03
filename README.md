# DataVisualisationProject
Detailed specification
You are to carry out a visual data exploration for ChrisCo, the fictional company whose sales and website data we have been analysing throughout the module, using a Python Notebook (in Colab or Jupyter).
ChrisCo is a fictional, but nonetheless very successful company managing a range of venues across the UK. ChrisCo collects a huge amount of data about individual customers visiting its venues using its loyalty card scheme but this customer data has been aggregated/averaged to give information about the company’s 40 venues, each identified by a unique 3 letter code (e.g. ABC, XYZ, etc).
Data
Each student on the module has their own, randomised version of the dataset to explore. You will find your data in the following csv files, where ID is your 9-digit student ID number (e.g. 001234567):
• https://tinyurl.com/ChrisCoDV/ID/VenueDailyVisitors.csv 
listing the daily number of visitors to the company's 40 venues
• https://tinyurl.com/ChrisCoDV/ID/VenueAge.csv 
the average age of visitors at each venue
• https://tinyurl.com/ChrisCoDV/ID/VenueDistance.csv
the maximum distance (miles) that visitors have travelled to each venue
• https://tinyurl.com/ChrisCoDV/ID/VenueDuration.csv 
the average time (mins) that visitors spend at each venue
• https://tinyurl.com/ChrisCoDV/ID/VenueGender.csv
the percentage of visitors identifying as female at each venue
• https://tinyurl.com/ChrisCoDV/ID/VenueSpend.csv 
the average spend (£) by visitors at each venue
Please contact the module leader if you cannot find your data files.
You should compile the data into two dataframes: one containing daily visitor data (one row for each date); the other containing summary data (one row for each venue), compiled from all of the .csv files, including the daily visitors.
