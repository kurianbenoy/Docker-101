# Docker-101

This is the code repo which I used for  IEEE Talks conducted on Topic `Docker 101`. Do checkout the slides here:https://speakerdeck.com/kurianbenoy/docker101

Regarding any doubts about installation [checkout for Docker](https://docs.docker.com/install/) and for [docker-compose](https://docs.docker.com/compose/install/).Choose appropriate installation for `Docker` and `Docker-compose` for your operating system.

For Debian-based distros install by:
```
 $ sudo apt-get remove docker docker-engine docker.io containerd runc
 $ sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg2 \
    software-properties-common
 $ curl -fsSL https://download.docker.com/linux/debian/gpg | sudo apt-key add -
 $ sudo apt-get update
 $ sudo apt-get install docker-ce docker-ce-cli containerd.io
``` 
[reference](https://docs.docker.com/install/linux/docker-ce/debian/)

If you have any doubts shoot me a mail or ping at my twitter handle
