# LendingClub-Demo
This demo involves using latest HDP w/ HDB2.0 (Single Node Edition Sandbox VM here: https://network.pivotal.io/products/pivotal-hdb).
It can also be run on any HAWQ/Greenplum env. This demo is to showcase HDB's ease of importing public data and quickly query and analyze the data. 

Pre-Reqs:

Download & run lc_demo_ddl_load_data.sql, which pulls data from an S3 bucket via external web table, which then loads internal hawq tables for loans completed and loans rejected for last 10 years. Create a lc_demo database then run the file using 'psql -f lc_demo_ddl_load_data.sql -d lc_demo ' . 
  
In Zeppelin, import 'LC_Demo.json', then edit PSQL Interpreter to connect to lc_demo database. Go to lv_demo note, and rerun queries or build your own. 


Note: original data is from https://www.lendingclub.com/info/download-data.action. 


enjoy :)
