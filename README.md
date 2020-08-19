# PrinInfo-DBTravelRes
Principles Of Information and Data Management Travel reservation Project
## Overview
## Importing
Front-end Java files and JSP files are contained in zip files. Please Note draft 1 does not have back-end.
This project connected the java files(with HTML/CSS contained within) to a locally hosted MYSQL 8.0 Server
via mysql-connector-java-8.0.19.jar and Tomcat v7.0 Server. To import the Database download the .sql file to a folder. 
Then using the MySQL Server Command Line client create an empty database with the same name(airlinedb). If it 
exists already use drop table. In Command Prompt cd to C:\Program Files\MySQL\MySQL Server 8.0\bin
Then run -h 127.0.0.1 -u root -p airlinedb<c:\folder_name\airlinedb.sql
Where folder_name is wherever the sql fil has been downloaded to.
