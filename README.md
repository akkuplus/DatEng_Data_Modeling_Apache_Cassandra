# Data Modeling With Apache Cassandra

## Summary

The demo project conducts ETL operations on CSV files and stores data in a Apache Cassandra database.   
This README summarized the underlying project to execute the Jupyter notebook. The notebook itself contains descriptions regarding the data models and the queries.

## Data
The data sets consists of a Event dataset (in subdirectory `event_data`), that contains CSV files. The CSVs show the following structure:
![images/img_1.png](img_1.png)

## Prerequisites

The project requires a *Python* environment having the packages:  
> pandas,  
> cassandra-driver,  
> jupyterlab  

and a *Apache Cassandra database* (database access: host=127.0.0.1).


## Getting Started
A running Python environment is assumed.  
Start the notebook  

    jupyter lab Project_1B.ipynb

and follow the notebook cells. 