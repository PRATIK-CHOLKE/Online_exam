# Online_exam
Online quiz
Steps To Execute Project:-

Step 1)
Download Xampp Server from 'https://www.apachefriends.org/download.html'.

Step 2)
Paste the project Online_exam inside 'C:\xampp\htdocs' directory of Xampp.

Step 3)
Also copy phpMyAdmin folder from 'C:\xampp' to 'C:\xampp\htdocs' directory.
Take note that your Project and phpMyAdmin is under same directory.

Step 4)
Open Xampp server and Start Apache and MySQL.

Step 5)
Open any of the browser and type 'http://localhost/phpMyAdmin/'
Enter the user name and password you have created while install MySQL on your device.

Step 6)
You will be directed to your phpMyAdmin panel.
  a)Inside it under Database section create new database 'quiz_new'.
      'http://localhost/phpMyAdmin/server_databases.php'
  b)Under Import section 'http://localhost/phpMyAdmin/server_import.php' Browse to location on your device 'C:\xampp\htdocs\Online_exam\database' and choose file 'quiz_new.sql.zip'
        
Step 7)
Now type in your browser 'http://localhost/Online_exam/'
You will be redirected to landing page of project. 
For admin login you can use 'http://localhost/Online_exam/admin/'
