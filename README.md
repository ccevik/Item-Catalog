# TheBackend-Database

Item Catalog Application  06/17/2017

General information about the app
------------------------------------
This application uses Flask,SQL Alchemy, JQuery,CSS, Javascript, and OAuth2 to create Item catalog website.

Please ensure you have Python, Vagrant and VirtualBox installed. This project uses a pre-congfigured Vagrant virtual machine which has the Flask server installed.

Setting up OAuth 2.0
-----------------------------------

1. Signup for a google account and set up a client id and secret.
2. Visit http://console.developers.google.com for google setup.


Setting up the Environment
----------------------------------

1. clone or download the repo into vagrant environment.
2. From your Terminal type command vagrant up,vagrant ssh.
3. Run python database_setup.py to create the database.
4. Run Python lotsofmenus.py to add the menu items
5. Run python 'project.py'
6. From your webbrowser and visit http://localhost:8000/
