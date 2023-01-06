# cool_web_app
Web application for study purposes  
The application is not cross-platform. Tested on Linux (Ubuntu). Should work on macOS (not tested).

## Installation

### Environment
set environment variable COOL_PORT to the port number you want to use  
set environment variable COOL_IP to the IP of the host machine

### Log
set environment variable COOL_LOG to the path where you want to store your server's log

### Content
To be able to create and change the content of you web application, create file cool-text.txt in the /usr/share/cool-app/ directory

### Application
Pull this repository to your machine
After everything is configured go to the root folder of the repository and run
```commandline
python3 run.py
```