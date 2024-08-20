A DEC VAX Notes Program for UNIX
================================

this is a replacement for the venerable VAX NOTES program.

It requires MariaDB to be installed on a UNIX system and a C compiler.To run the notes.c program along with its associated components (init_db.c, user_manager.c), you will need several packages installed on your operating system. Below is a list of the required packages:

apt-get install libmariadb-dev  
apt-get install libmysqlclient-dev  
apt-get install mariadb mariadb-devel  


Build
-----

get this repository
then do 
make

     
That's it.   

    
Configure
---------
  
Initialize the Mariadb database with init_db.
  
Add users with user_manager add user userpasswd.
  
List users with user_manager list
  
Remove users with user_manager remove user

    
Run NOTES
---------
   
from the UNIX command line invoke ./notes and then login with the userid and password given to you by the NOTES administration when she/he createdteh database
  
There are 2 screens: TOPICS and FOLLOWUPS. 
  
In the TOPICS screen you see all NOTES topics (also sometimes called conferences). And in the FOLLOWUPS screen you see response and followups to the topic of conference.   

Easy  

Enjoy  

Moshix  
August 19, 2024

