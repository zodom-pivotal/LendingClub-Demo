# LendingClub-Demo
This demo involves using latest HDP w/ HDB2.0 (Single Node Edition Sandbox VM here: https://network.pivotal.io/products/pivotal-hdb).
It can also be run on any HAWQ/Greenplum env. 

Pre-Reqs:

Download & run lc_demo_ddl_load_data.sql, which pulls data from lendingclub site via external web table, which then loads internal hawq tables for loans completed and loans rejected for last 10 years. Create a lc_demo database then run the file using -d lc_demo. 
  
Import Zeppelin json, 'LC_Demo.json', then edit Interpreter to connect to lc_demo database. 


Note: original data is from https://www.lendingclub.com/info/download-data.action. 


