# Predicting-Recession
Analyzed historical US data from various sources to predict the US recession using ML
The process of data cleansing is as such:
We took the Unemployment Rate, Consumer Price Index, and Bond Rate from the Federal Reserve Economic Database (FRED). 
- The data is fortunately curated to be easily adjustable, so I set the date range of the datasets to January 1st, 1948 - October 1st, 2023 for each dataset we used. The frequency was per month. (910 months in total)
- This allowed us to download the data as .csv files, with a “DATE” column and “[Economic Indicator]” column. For example, the Unemployment Rate dataset was a table with a “DATE” column starting at 01-01-1948 and a “UNRATE” column with the percentage of unemployment for each month.
- This made cleansing the data a non-question, I didn’t even have to organize the data to a consistent form because FRED let the date range and frequency we wanted, and since I got the data from the same database, they all had the same uniform format.

  Further details about our methodology and results are included as PPt file in this repository.

  
