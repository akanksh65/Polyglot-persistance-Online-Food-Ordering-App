# Polyglot-persistance-Online-Food-Ordering-App
In this project we'll be conceptualising and implementing a database-driven application where multiple database technologies(Relational Database(SQLLite) amd noSQL(Redis)) co-exist within the same application.

We'll be using pandas and SQLAlchemy(ORM) to play with the Database:)

Link to our project presentation : https://www.dropbox.com/s/1juruk84k1w8krk/BEMM459-Final_Presentation.mp4?dl=0


NOTE : Change the location of csv files as needed beforing running the code. CSV files can be directly read through this github link as well.

## -> Database technologies used:
                               1) RDBMS(relational Database Management System)(SQLLite3)
                               2) Redis( NoSQL database system)(redis-cli Version 3.0.504)

# -> Tools used to implement:
                          1) redis-cli and redis-server
			        2)Jupyter notebook luanched with the help of Anaconda Navigator
                          3) Python version 3.3 (Please refer to the python syntax carefully if using lower versions as there mught be slight changes)


 ## ->Objective of the application:
			1) Our application will assist three types of users,namely:
                                    I)Customers who place order
                                    II)Software vendors/partners who will process the payment
                                    III)Restaurant owners who'll update address and menu items
                        2) Objective of this application is to ensure smooth transaction between all three types of users
                        3) Also provide appropriate access to each users so that there is no data breach

NOTE : The Video presentation has been uploaded in the one-drive and the link has been shared inside the powerpoint presentation.
(or) Please refer to Video_Recording_Link.txt for the presentation link.

## ->HOW TO INSTALL AND RUN THE APPLICATION:
      #                                                      RDBMS.ipynb
                                     1)Make sure all the files in the zip file are stored in this location(S:\BEMM463_Group_Assignment).
                                     2)Do not change the folder name or the .csv file names.
                                     3)Open anaconda navigator
                                     4)Open jupyter notebook
                                     5)Directly run and execute the RDBMS.ipynb file
                                     6)The BEMM459_ASSIGNMENT.db file will be saved in downloads if you would like to view it in sqllite3
                                     NOTE : If you're rerunning the code, please delete the database file and then rerun it(Downloads/BEMM459_ASSIGNMENT.db) 
                  
    #                                                        NoSQL(Redis).ipynb
                                     1)Please type redis-server and open redis-server.exe. Keep it open until all the codes are run
                                     2)As we're using default port(6379), we can now proceed with the jupyter notebook file
                                     NOTE :The SCAN function will work only on Redis-cli higher than 2.8.Exeter's Virtual Windows Desktop has redis-cli version 2.4.5 which is not compatible with SCAN, HSCAN functions
                                     3)(You can update redis-cli using this link(https://github.com/microsoftarchive/redis/releases/download/win-3.0.504/Redis-x64-3.0.504.msi))
                                       You can also run the .msi file provided in the zip file to install latest redis cli
