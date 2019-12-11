This project is titled 'Hair By Dalton'. It is a website prototype built for a local 
hairstylist, intended to be the first of many other iterations built for other servicers. 
The website is built with a MERN (MongoDB, ExpressJS, ReactJS, NodeJS) stack. This specific 
folder is the folder containing the back end code. There is another folder called 'hairwebsite-web'
that contains the front end code. This website should be live and accessible at the url 'https://hairbydalton.com'.

In order to run this project locally, NPM (NodeJS Package Manager) version 6.9.0 must be installed and
NodeJS version 10.16.3 must also be installed. This can be done by visiting this link 'https://nodejs.org/en/'
and installing the appropriate version of NodeJS (which will include NPM with it).

>cd into the hairwebsite-backend folder in a terminal window 
>run 'npm install' in the directory
>run 'npm start dev' to start the api server
>cd into the hairwebsite-web folder in a terminal window 
>run 'npm install' in the directory
>run 'npm start' to start the front end

This should open a localhost version of the website in the browser that has an api to communicate with.
This is more easily done on a Mac or Linux machine, but can be done on Windows too. Alternatively, navigate
to 'https://hairbydalton.com' to use the website. In order to test the administrator view, log in with
'admin@hairbydalton.com' for the email and 'hbdadmin' as the password. This will allow the stylist to view
all upcoming events on the scheduling calendar.

Known Issues:
- Inconsistent input validation for registration page
- Inconsistent input validation for login page
- Users are sometimes still able to create appointments that overlap with existing events

Developed by Jacob Khoury.