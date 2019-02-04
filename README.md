# docker-windows-server

This is a very simple Microsoft IIS website that allows a user to send a tweet. 

This is part of the Docker for Window Servers series from [56K.Cloud](www.56k.cloud) This exercise is about configuring Windows Servers for a Docker development environment.

Requirments

* Windows Server OS: Server 2016 (Core and GUI), 1709 and 1803
* Configure at least 100GB for Disk Space as this fills up quickly
* Run Windows update to get all the latest patches
* Install Docker for Windows servers - https://docs.docker.com/install/windows/docker-ee/
* Install docker-compose - https://docs.docker.com/compose/install/

To use it:

```Build it: docker build -t windows_tweet_app . ```

Run it: 

```docker container run --detach -p 80:80 windows_tweet_app```