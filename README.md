
# Library Management System

This project is a GUI-based Library Management System implemented using Python and Tkinter.
It is the coverted copy in exe format using pyinstallerto, to run in windows application.
>> Password for unzip is >> 123

You can also convert the python program "https://github.com/md-arbaz98/abzlms" into exe using pyinstaller.
Process -
Install pyinstaller using >> pip install pyinstaller . 
Can create/modify arbazLMS.py from "https://github.com/md-arbaz98/abzlms" as per your need. 
then,
change cmd directory to the application folder and run that cmd command there 
>> pyinstaller --onefile --add-data "logo.png;." --add-data "dues.json;." --add-data "authors.json;." --add-data "books.json;." --add-data "borrowers.json;." arbazLMS.py

it then build you .exe application in build folder.
Copy all of your json files to build folder where arbazLMS.exe is build and its done.

 
## License

*MIT LICENSE*
