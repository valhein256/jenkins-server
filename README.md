# Jenkins
Ref:
- https://hub.docker.com/_/jenkins

## Build jenkins
```shell
$ docker pull jenkins
```
## Run 
```shell
docker run -p 8080:8080 -p 50000:50000 -v ${PWD}/jenkins_home:/var/jenkins_home jenkins/jenkins:lts
```
