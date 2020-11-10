Backjam Community Edition
==================================================

Backjam allows enterprise-grade backups across all of your devices.

The server component stores the devices' data, and comes with a web-based administration interface.
Devices with the Backjam desktop client installed can sync data to the server for backups and restore at a later date.

The Community Edition of Backjam server allows the server component to be run as a docker image 
on your machine or premises, giving you total control of what you back up.

More info at https://www.backjam.com.

# Requirements
--------------

- Docker and Docker Compose to run the server component.
- A Mac OSX or Microsoft Windows device to back up data. More operating systems to be supported at a later date.

# Getting Started
------------------

1. The given `docker-compose.yml` file demostrates how to pull the Backjam CE docker image and run. 
Simply run the Docker container as:

.. code-block::

    docker-compose up

By default, the web administrative interfacce is available on `http://localhost:3000`. 
Create a user account to get started. 

2. Download the client desktop software in the `downloads` folder for your respective OS.

On Windows, Backjam client needs to run as Administrator mode to install.

On Mac OSX, Backjam client requires permissions under Preferences > Security & Privacy to install.

3.  When the client app loads with the Sign In screen, change the settings and update the API server 
and point to your Backjam server.

4. Sign in with your created credentials to start.


# Further information
---------------------

Backjam Community Edition docker image is hosted at:
https://hub.docker.com/r/casadila/backjam-ce

Backjam is still a work in progress. 
Send feedback or bugs to feedback@backjam.com.

# Warranty & Disclaimer
-----------------------

There is no warranty, use at your own risk!
