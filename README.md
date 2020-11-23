# Library-managment
This is the project of Library managment system 1.0

requirements:

*) MYSQL  community server
*)MYSQL JDBC connectors
*)java
*)eclipse ide
*)rs2xml.jar file - download link - 
https://sourceforge.net/projects/finalangelsanddemons/files/rs2xml.jar/download
This project has 5 methods
login()
connect()
create()
user menu()
admin menu()

SWING - graphical user interface components such as scroll bars, buttons, dialog boxes, etc can be created using swing
LOGIN() - this function to enable the user and the admin login. So, initially when a user logs in for the first time, that user will be an admin by default, and the username and password will be {admin, admin}.
CONNECT() - The connect function is used to connect the database to the GUI.  here it is connecting to our 
MySQL database with the username “root” and password “sriram” to our application. Now, once the application is connected to the database, our next step is to create or reset the database.
CREATE() - The create function is used to create the database, tables and add data into these tables. 
USERMENU() - The User Menu is designed to show details of all the books present in the library and the books issued by the user.
ADMINMENU() - The Admin Menu is designed to show details of users, books, issued books, add books, return books, add user, and create or reset the database.
