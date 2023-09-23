The objective of this project was to help CMU students like myself find housing that matches my preference because good properties are highly sought after. The project was divided into 
1.) automating real estate properties data collection
  -This is done with a python webscrapping script
  -In addition, I use a third party python api to find the neighborhood of each property to be use as foriegn key for other table with neighborhood statistics data
2.) designing an database schema to store the data for analysis
  -Because the data volume is no low, and the project scope is limited, a STAR-schema data warehouse is implemented without storing in a ER Model OLTP database.
  -ran ETL process on data warehouse from multiple sources
3.) finding properties by  queries
  Ran SQL queries to find attractive housins

