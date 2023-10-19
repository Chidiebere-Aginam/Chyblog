## Chyblog Web Application

This web application is a blogsite used in posting various topics 
for viewers to read, get enlightened and then make comments if need be. 
First and foremost, users need to register before they will be granted 
access to log in with valid credentials else validators would flag errors.

## Author: Chidiebere Aginam

## links

https://www.linkedin.com/in/chidiebere-aginam-51b22b128
https://www.twitter.com/ChidiAginam

E-mail: chidiebereaginam@yahoo.com

## Installation:

Create a virtual environment, install python3 alongside all the dependencies
of the file; requirements.txt found in the root directory.
Acquiring appropriate server preferably Ubuntu and loading the files to the correct folders,
this website can be run smoothly having installed a webserver and a relational database probably postgresql.

Prior to upload, this package can be tested in a local development server by running the following command 
in the terminal:

python3 run.py

## User Requirements:
1. Username
2. Password
3. E-mail
4. Profile picture

## Challenges

1. SMTP Authentication Error: it displayed application-specific password required in the terminal development environment on testing the reset password/token aspect. I applied several tacts ranging from reconfiguration of dundee init file to the modification of the serializer method by changing some of the deprecated parameters with reference to documentation to suit the arguments. Summarily, this error was cleared by logging on to Gmail settings, generating an application password of length sixteen characters as a new security ruling by Google in handlilng applications instead of setting a password as an environment variable.
2. Incompactibility of Flask-Bcrypt and hashed passwored: This failed to install using the pip command but was resolved by providing its dependencies. Another issue is the creation of hashed password, got around it by making reference to documentation.
3. Creation of token with itsdangerous library: This took me time because the last time I used it, the argument; expires_in and the module; TimedJsonWebSerializer were all in one place. Little did I know that it has changed. I logged on to python interpreter, figured out its modus operandi and lastly applied that.

## Screen Shots

![](https://github.com/Chidiebere-Aginam/Chyblog/img/chyblog1.png)
![](https://github.com/Chidiebere-Aginam/Chyblog/img/chyblog2.png)
![](https://github.com/Chidiebere-Aginam/Chyblog/img/chyblog3.png)
![](https://github.com/Chidiebere-Aginam/Chyblog/img/chyblog4.png)
![](https://github.com/Chidiebere-Aginam/Chyblog/img/chyblog5.png)
