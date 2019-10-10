# Basic-ETL-Pipeline

## What is ETL?
ETL is actually short form of **Extract, Transform and Load**, a process in which data is acquired, changed/processes and then finally get loaded into data warehouse/database(s).

Basically, ETL entails **Extracting** data from a source like a Website, or Database, followed by **Transforming** this data to a format that the usecase requires and finally **Loading** to a database or data warehouse

This Repo will illustrate out a way on how to create an ETL pipeline

So to accomplish that we will be:
* Extracting data from a CSV file already provided in the repo
* Transforming/Manipulating Data
* Loading Data into MongoDB

But first thing first we need to install some python libraries, to do that run this command

```
$ python -m pip install -r requirements.txt
```

Once this is done, You can check out the notebook dir for more info on how to create an etl pipeline
We will be using the cryptocurrency dataset for the year 2013 to 2014