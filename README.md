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
In Postgesql,I analyse data check and perform some data cleaning like check for Duplicates Values,Missing values etc.
Some of the column Rows contain more than one value like Genre column there are many Shows which are listed in more than one genre so I created a seperated table for genre and link them using show id column as i set it as primary key column becouse it doesnt contain any duplicates, Similarly i did this for some other column also like director,country etc.
Handle missing Value in country,date added column .
