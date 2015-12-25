# DailyDeals
Data visualisation 
Visualization showing comparison between dailydeal sites


In this task we have compared four main daily deal sites Groupon, AmazonLocal, LivingSocial and KGBDeals based on their quarterly revenues for years 2010,2011 and 2012 along with discount offered in each quarter of each year.It shows how revenues of companies varied all these years and what and how much effect did discount had on it.

Pre-Requirements
1. Mongodb
2. Flask framework
3. Pymongo(optional)
4. Robomongo(optional)

Steps Followed

Creating Required Database
Install Mongodb
Import the main database in form of csv file
Perform the operation in Mongo to derive collections
can export the collections if needed
Robomongo can be installed and used for making required collections.

Using Flask Framework
python framework is used  for connecting html file to browser and providing it a route.
We can create a data api using pymongo and importing data from mongodb
all the changes made are simultaneously uploaded on browser       

Creating graph
Graph is created in html file using HTMl,CSS,D3.js and javascript
Here we have used grouped bar chart to show quarterly revenues of companies
discount offered by each company is also shown.

Folder Structure

static           groupon.csv
                    livsocial.csv
                    kgbdeals.csv
                    ama.csv

  templates          index4.html
                  
app.py

formulas.txt


1. static folder: it contains database for various sites in form of csv files
2. templates: it contais html file which contains main graphs work
3. app.py : this file contains framework and it needs to be run


How to run the project

Download the folder from git here
Download flask
Enter the directory where app.py is placed
$python app.py
open the link and see the results
