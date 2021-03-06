# turnie.re Quick start guide

To get the current stable version of the turnie.re website running on your machine you don't need anything more than this repository. We preconfigured a docker-compose file with all the containers you will need to run, so everything you have to do is run `docker-compose up` within this directory and everything will be set up by the docker daemon in a few seconds.

If you want to access it from another machine, you will need to open both port 3000 and 80 for back and frontend and also in docker-compose change the TURNIERE_API_URL from `localhost` to whatever the IP of the machine you are running it on is.

To install Docker on your machine just use the package manager of your choice or if it doesn't have a docker package you can look [here](https://docs.docker.com/install/linux/docker-ce/ubuntu/). For [Mac](https://docs.docker.com/docker-for-mac/install/) or [Windows](https://docs.docker.com/docker-for-windows/install/) please refer to the official install Guide from Docker Inc.

## TL;DR
```
$ git clone https://github.com/turniere/turniere-quickstart
$ cd turniere-quickstart
$ docker-compose up
$ # this will start the backend on port 3000 and the frontend on port 80
```
Open http://localhost/ with your preferred browser.
