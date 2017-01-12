# docker deploy

Educational example for docker image build automation (DIY).

**This is intended for educational purposes only - not for production!**

## Setup

1. Install [docker](http://docker.io).
2. Install [docker-compose](http://docs.docker.com/compose/install/).
3. Clone this repository

## Usage

Start your stack using *docker-compose*:

    docker-compose up

Alternatively use [Vagrant](https://www.vagrantup.com/)

    vagrant up

Then hit the UIs for

- [Gogs](https://gogs.io/) at [http://localhost:3000](http://localhost:3000)
- [Jenkins](https://jenkins.io/) at [http://localhost:8080](http://localhost:8080)
- [Docker Registry](https://github.com/kwk/docker-registry-frontend) at [http://localhost:80](http://localhost:80)

## References

- [Running Docker in Jenkins (in Docker)](http://container-solutions.com/running-docker-in-jenkins-in-docker/)
- [How To Build Docker Images Automatically With Jenkins Pipeline](https://blog.nimbleci.com/2016/08/31/how-to-build-docker-images-automatically-with-jenkins-pipeline/)