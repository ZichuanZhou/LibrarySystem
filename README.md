# LibrarySystem
				--------	
				|README|
				--------	
Version 1.0 Oct 2015
=====================================================================

Application Developed: Zhulin Temple Library Management System
=====================================================================
			       -----------	
			       |Developer|
			       -----------
Zichuan Zhou, zhou0307@uni.flinders.edu.au
=====================================================================
			 	 -------	
				 |INTRO|
				 -------
This application is designed for Zhulin Temple Library for their
library daily management.

This application is developed by Netbeans IDE 8.0.2,database management 
system is MySQL 5.6,and it could be implemented under Windows and Mac.
=====================================================================
			         -------	
			         |FILES|
			         -------
Java File:      	/LibrarySystem.zip
SQL File:   		/library.sql
JAR File:        	/JAR/mysql-connector-java-5.1.23-bin.jar
			/JAR/swingx-1.6.1.jar
=====================================================================
			         ------------	
			         |DEPLOYMENT|
			         ------------

Open NetBeans IDE, import project from LibrarySystem.zip.
The project should already include two JAR files,
if not, please add jar files from JAR folder into the project Libraries.

Run library.sql file to create new database and tables into local database
server.

After open the project, in Services create a new database connection named
library, then go to Source Packages/control/Dao.java,from line 16 to line 
20,change the global variables dbUser, dbPwd,dumpExePath to your local 
database user name, password and installation path

=====================================================================
