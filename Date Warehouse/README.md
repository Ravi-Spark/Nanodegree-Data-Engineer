**Introduction:**
A music streaming startup, Sparkify, has grown their user base and song database and want to move their processes and data onto the cloud. Their data resides in S3, in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.

As their data engineer, you are tasked with building an ETL pipeline that extracts their data from S3, stages them in Redshift, and transforms data into a set of dimensional tables for their analytics team to continue finding insights in what songs their users are listening to. You'll be able to test your database and ETL pipeline by running queries given to you by the analytics team from Sparkify and compare your results with their expected results.

Their user activity and songs metadata data resides in json files in S3. The goal of the current project is to build an ETL pipeline that extracts their data from S3, stages them in Redshift, and transforms data into a set of dimensional tables for their analytics team to continue finding insights in what songs their users are listening to.


**Follow the process to run the project :**

a. Put Credential dwh.cfg accordingly (AWS)    

b. Run the create_tables.py to set up the needed infrastructure for this project.         

c. Finally, execute the etl.py script to extract data from the files in S3, stage it in redshift, and finally store it in the dimensional tables.             

**Project Files:**
"dwh.cfg" for aws Credential configuration    
"create_tables.py" drops and creates tables. You run this file to reset your tables before each time you run your ETL scripts.   
"sql_queries.py" contains all your sql queries (create, drop and insert data)      
"etl.py" reads and processes data and loads them into your tables
