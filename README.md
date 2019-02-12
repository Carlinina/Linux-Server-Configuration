# Linux-Server-Configuration

It take a baseline installation of a Linux server and prepare it to host my web application.
The server is a LightSail Amazon server, running ubuntu 18.
Server is secure from a number of attack vectors.

## Requirements

1. Computer (Windows or Mac OS)
2. Working knowlage of using the command-line.
  
## Instructions

1. Download the project
2. Use the "grader" key to connect to the server 
3. Use the following command to connect to ssh: " ssh -i grader grader@35.158.229.147 -p 2200"
4. The passphrase is "grader"
3. The public url of the catalog project is http://35.158.229.147.xip.io
4. Enjoy!

## Third party resources

1. Install apache
```sudo apt-get install apache2```
2. Install python2
```sudo apt-get install python2.7```
3. Pip, installed by executing the following commands, 
* ```sudo apt-get install python-pip python-dev build-essential``` 
* ```sudo pip install --upgrade pip``` 
* ```sudo pip install --upgrade virtualenv``` 
4. Once in the project directory 
```cd /var/www/catalog/catalog``` 
```pip install sqlalchemy```
