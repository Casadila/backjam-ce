# Backjam Community Edition

Backjam allows enterprise-grade backups across all of your devices.

The server component stores the devices' data, and comes with a web-based administration interface.
Devices runs a Backjam client desktop to sync data to the server for backups and restore.

The Community Edition of Backjam server allows the server component to be run as a docker image 
on your machine or premises, giving you total control of what you back up.

More info at https://www.backjam.com.

## Requirements

- Docker and Docker compose to run the server component
- A Mac OSX or Microsoft Windows device to back up data. Currently only Mac and Windows is supported at this time.

## Getting Started

1. The given `docker-compose.yml` demostrates how to pull the Backjam CE docker image and run. 
Simply run as:
    
    docker-compose up
   
By default, the administrative site is available on `http://localhost:3000`. 
Create a user account to get started. 

2. Download the client desktop software in the `download` folders for your respective OS.

On Winwodws, Backjam client needs to run as Administrator mode to install.

On Mac OSX, Backjam client requires permissions under Preferences > Security & Privacy to install.

3.  When the client app loads with the Sign In screen, change the settings and update the API server 
and point to your Backjam server.

4. Sign in with your created credentials to start.


## Further information

Backjam is still a work in progress. 
Send feedback or bugs to feedback@backjam.com.

## Warranty & Disclaimer

There is no warranty, use at your own risk!
    