# docker-git

A Docker container for the git client and other system utilities provided by Alpine (e.g. BusyBox) and Curl.

## Examples

```
docker run -v /home/adam:/var/data channeladam/git git clone https://github.com/channeladam/git-docker.git

docker run -v /home/adam:/var/data channeladam/git ls
docker run -v /home/adam:/var/data channeladam/git wget http://blah...
docker run -v /home/adam:/var/data channeladam/git curl http://blah...

```
