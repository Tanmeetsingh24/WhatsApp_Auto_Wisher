# WhatsApp_Auto_Wisher
This project simplifies the task of keeping up with birthdays and anniversaries by automating the process using Python and MySQL softwares along with an effective user interface.

### Features of the project:
Working: ON successfully running the code, an interface asking for your name and the birthday wish you to send. After submitting the form, it takes you to a interface where all you do is confirm sending you message by pressing enter. The code automatically picks up the name and phone number of the person from the database and sends the wish via WhatsApp.

Softwares Used: In this project, we have used Python Programming Language (Version-3.7 and IDE-Jupyter Notebook) and its built in libraries like pymysql (Database Management)and Tkinter (GUI Development).The project also explores MySQL through phpMyAdmin (Server-127.0.0.1) and uses a subset of queries to work in between Python and MySQL softwares.

GUI Development: We have used tkinter Python Library for presentable/attractive GUI developement. Alongside using tkinter options like Frame, Buttons, Labels, Headings and Entries, we use used the keyword 'self' with all functions to avoid the attribute error from occuring.

MySQL: Using the XAMPP Control Panel (Version-3.3.0), we have created a table 'contact' in the database 'whatsapp' using MySQL through phpMyAdmin (Server-127.0.0.1). The columns along with their datatypes are SNo int(2), Name varchar(20), Birth_Date varchar(4), Phone_No bigint(10).

OS Module: We have used the OS module in Python to provide functions for creating and removing a directory (folder), fetching its contents, changing and identifying the current directory, etc. The module links our source to WhatsApp Operating System.
