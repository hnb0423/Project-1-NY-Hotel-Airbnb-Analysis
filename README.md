# Project 1: NY Hotel and Airbnb Analysis

The goal of this project is to analyze and visualize factors that characterize high quality hotels and Airbnbs in New York State and provide travellers with optimal decision that best suit their needs. I use Python, OpenRefine, R, SQL, MongoDB, and Tableau for data processing, data analysis, and data visualization. 

1.1 Raw Data:

●	Hotel: https://www.programmableweb.com/news/10-top-apis-hotels/brief/2019/09/08 <br/>
●	Airbnb: http://insideairbnb.com/get-the-data.html <br/>
●	Hotel properties:https://data.cityofnewyork.us/City-Government/Hotels-Properties-Citywide/tjus-cn27 <br/>
●	Restaurant: https://data.cityofnewyork.us/Health/restaurant-data-set-2/f6tk-2b7a <br/>

1.2 Data Cleaning and transformation: 

●	All data are in csv format<br/>
●	Cleaning process: <br/>
a.	Use OpenRefine and Excel to cluster and clean excessive and repetitive rows. <br/>
b.	Use Python to drop unnecessary columns and conduct a normalization process. See python files <br/>
i.	‘NY Airbnb & NY hotel Clean Steps.ipynb’  for normalization process <br/>
ii.	‘Hotel_properties_clean.ipynb’ <br/>

1.3 Data Storing

●	Export from OpenRefine in csv file. <br/>
●	Load data into SQL using import wizard. <br/>
●	Load data into MongoDB using terminal common lines. <br/>

In SQL: <br/>
●	Created schema called ‘hotel’ <br/>
●	Create database using the SQL file ‘SQL Data Import.sql’ <br/>
●	Used SQL queries to generate insights <br/>
In MongoDB <br/>
●	Created schema called ‘NYDB’ using file ‘Mongo DB Data import.txt’ <br/>
●	Used MongoDB queries to generate insights <br/>

1.4 Visualization & Models

Tableau: Connect SQL server to Tableau  <br/>
●	Workbook ‘Data Visualization.twbx’ <br/>

SQL: <br/>
●	Used SQL queries to generate insights

MongoDB: <br/>
●	Used MongoDB queries to generate insights

R: <br/>
●	Used R to generate text cloud, r file ‘text-analysis.RMD’ <br/>
●	Used R to generate linear regression, logistic regression, random forest model ‘R-Analysis.RMD’. 


