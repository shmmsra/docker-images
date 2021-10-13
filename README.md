# docker-images
A bunch of preconfigured docker image configs for different purposes

## Build docker image
Use the following commands to build and run any of the dockerfile in this repo:
* `cd ubuntu/`
* `docker image build -t "shmmsra/ubuntu:dev" .`
* Mac: `docker run -it -v "~/Documents:/home/dev/Documents" "docker.io/shmmsra/ubuntu:dev" bash`
* Win: `docker run -it -v "C:\Users\shmishra\Documents:/home/dev/Documents" "docker.io/shmmsra/ubuntu:dev" bash`
