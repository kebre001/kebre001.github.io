---
layout: post
title: Learn linux 2 - Services and demons
category: posts
---

## What to learn in this chapter
How to handle services, server software and daemons.
 

### Daemons
Systems often start daemons at boot time and serve the function of responding to network requests, hardware activity, or other programs by performing some task. Daemons can also configure hardware (like udevd on some GNU/Linux systems), run scheduled tasks (like [cron](http://en.wikipedia.org/wiki/Cron)), and perform a variety of other tasks.

Later on I want you to try installing an [apache](http://en.wikipedia.org/wiki/Apache_HTTP_Server) server which is a webserver.
Since there really is no output of that program that is interesting for you to see the only relevant thing to do is to run it as a daemon and let the system run it in the backgrund without disturbing you and fill your terminal with rubbish.

*(apache is a software which is designed for unix/linux and therefor is included in the apt-get library)*

Almost all server software does run as a daemon because its purpose is to serve/process in the backgrund to all the users/clients.

Also software that is supposed to run as a daemon ends often with 'd', for example a FTP-server in linux is called ftpd. The SSH daemon is sshd,

**Examples of software to run as daemon:**

- [Teamspeak server](http://teamspeak.com/?page=downloads)
- FTP server
- SSH Server ([OpenSSH](http://en.wikipedia.org/wiki/OpenSSH))

All of these can you find in the linux library with 'apt-get'



