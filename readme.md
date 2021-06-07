#Primavera
This project collects all files for the progressive web application Primavera. This web application aims to support women during menopause journey. 

###Getting started
The following instructions will get you a copy of the project up and running it on you local machine. See deployment notes on how to deploy the project on a live system.

###Set up
In order to set up the project, follow the step by step example.
* Open Intellij
* Navigate to File -> New -> Project from Existing folder -> navigate to the downloaded file
* Click 'OK'.
* Then the project has to open on the local machine

Note: Make sure you have added the external libraries. Otherwise, the interactive components will not be rendered. To accomplish this, open one of the HTML files (e.g. index.html) and where the link and script tags are highlighted in yellow, right click on them, Show Context actions and then allow downloading of the libraries. 

 
###Deployment
In order to deploy the project, follow the step by step example.
* In Intellij, navigate to Tools -> Deployment -> Configuration 
* Click on '+' button and choose SFTP
* Then, add as a host cafe.cis.strath.ac.uk
* Navigate to the root path where you would like to store the files and to deploy them
* In the Mapping section, add /Primavera to both paths 
