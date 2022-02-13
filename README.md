# Project 1 NY Hotel and Airbnb Analysis

The goal of this project is to analyze and visualize factors that characterize high quality hotels and Airbnbs in New York State and provide travellers with optimal decision that best suit their needs. I use Python, OpenRefine, R, SQL, MongoDB, and Tableau for data processing, data analysis, and data visualization. 

1.1 Raw Data:

●	Hotel: https://www.programmableweb.com/news/10-top-apis-hotels/brief/2019/09/08
●	Airbnb: http://insideairbnb.com/get-the-data.html
●	Hotel properties:https://data.cityofnewyork.us/City-Government/Hotels-Properties-Citywide/tjus-cn27
●	Restaurant: https://data.cityofnewyork.us/Health/restaurant-data-set-2/f6tk-2b7a

1.2 Data Cleaning and transformation: 

●	All data are in csv format
●	Cleaning process:
a.	Use OpenRefine and Excel to cluster and clean excessive and repetitive rows. 
b.	Use Python to drop unnecessary columns and conduct a normalization process. See python files
i.	‘NY Airbnb & NY hotel Clean Steps.ipynb’  for normalization process 
ii.	‘Hotel_properties_clean.ipynb’

1.3 Data Storing

●	Export from OpenRefine in csv file. 
●	Load data into SQL using import wizard.
●	Load data into MongoDB using terminal common lines. 

In SQL:
●	Created schema called ‘hotel’
●	Create database using the SQL file ‘SQL Data Import.sql’
●	Used SQL queries to generate insights
In MongoDB
●	Created schema called ‘NYDB’ using file ‘Mongo DB Data import.txt’
●	Used MongoDB queries to generate insights

1.4 Visualization & Models

Tableau: Connect SQL server to Tableau 
●	Workbook ‘Data Visualization.twbx’

SQL:
●	Used SQL queries to generate insights

MongoDB:
●	Used MongoDB queries to generate insights

R:
●	Used R to generate text cloud, r file ‘text-analysis.RMD’
●	Used R to generate linear regression, logistic regression, random forest model ‘R-Analysis.RMD’. 


