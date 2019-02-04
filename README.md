# docker-windows-server

This is a very simple Microsoft IIS website that allows a user to send a tweet. 

This is part of the Docker for Window Servers series from [56K.Cloud](www.56k.cloud) This exercise is about configuring Windows Servers for a Docker development environment. 

To use it:

```Build it: docker build -t windows_tweet_app . ```

Run it: 

```docker container run --detach -p 80:80 windows_tweet_app```


