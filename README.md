# Amazon-Prime-Video-ELT
**Overview:**
Evaluated the dataset to identify the top country, director, and genre other useful insights that shaped content acquisition for Prime Video.

**Approach:**
In this project,I Followed ELT(Extract Load Transform) Approach Which involves extracting data from source then loading it to appropiate database where we 
Clean and transform data to useful format then extract Insigth.

**1.Extract:**
I extract dataset from it source using opendatasets and import it to jupyter notebook using pandas.

**2.Load:**
For loading data from jupyter notebook to Postgresql database I used SqlAlchemy,mysql connector and pandas library.

**3.Transform:**
In Postgesql,I analyse data, check and perform some data cleaning like check for Duplicates Values,Missing values etc.I check for duplicate value of show_id and make it as primary key.
Some of the column Rows contain more than one value like Genre column there are many Shows which are listed in more than one genre so I created a seperated table for genre containing show_id and genre column and link this table with main table by show_id column, Similarly I did this for some other column also like director,country etc.
Handle missing Value in country,date added column etc.
After Cleaning data i extracted Insight from data using Advance SQL queries.
Finally I load this data from posgresql to Power Bi and Created Interactive dashboard by utilizing Dax for easy understanding by stakeholders.

**Key Findings:**
-United states and India are top contributing country in content uploading on prime.
-Maximum shows are of Drama,comedy and action genre respectively.
-Top contributing directors are Mark knight and Cannis Holder respectively.
-Number of movies are more than TV shows.

**Tool Used:**
-Python
-SQL
-Power Bi

**Tool Learning:**
- Python for extracting and cleaning data
- Advanced SQL queries
- Power BI DAX

dataset link :https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows

Please feel free to give any suggestion or feedback, If you like this post give it a like and share it.
Follow me on github and linkedin for more useful data analyst project

Github profile:https://github.com/ShahRizwan007/Amazon-Prime-Video-ELT/edit/main/README.md

Linkedin profile:https://lnkd.in/dJguGPtK
