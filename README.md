# Movies-ETL

## Summary

Amazing Prime wants to keep their dataset updated on a daily basis. They requested an automated pipeline that takes in new data, performs the 
appropriate transformations, and loads the data into the existing tables. Existing code was refactored to create one function that takes in the 
three files:

- Wikipedia data
- Kaggle metadata
- MovieLens rating data
and performs the ETL process. 

It then adds the data to a PostgreSQL database.

