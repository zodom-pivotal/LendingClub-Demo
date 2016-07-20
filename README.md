# LendingClub-Demo
This demo involves using latest HDP w/ HDB2.0 (Single Node Edition Sandbox VM here: https://network.pivotal.io/products/pivotal-hdb).
It can also be run on any HAWQ/Greenplum env. 

run file.sql, which pulls data from this repository or pull down and load locally and loads internal hawq tables for loans completed and loans rejected for last 10 years. I created a lc_demo database then ran the file using -d lc_demo
  
Import Zeppelin json, 'LC_Demo.json', then edit Interpreter to connect to lc_demo database


