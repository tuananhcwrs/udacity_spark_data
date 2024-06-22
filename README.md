# Project Files
## dl.cfg
configuration file contains your aws secret

## etl.py
python script that loads song data and log from S3 to Spark, transforms data into tables and stores them back to S3

## README.md
project info file

# Instruction
## Set aws configuration in dl.cfg
AWS_ACCESS_KEY_ID = <your aws key>
AWS_SECRET_ACCESS_KEY = <your aws secret>
    
## Use following command to start ETL process
python etl.py