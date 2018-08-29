WiseBuild
=================
WiseBuild   is a web application  about CI/CD  

## Check environment

* docker  -v 
* docker-compose  -v

## Run Server and Restart

```
docker-compose up -d 
docker-compose restart
```
## The Index URL

```
< HOST >:8081
```
the defalut account
* name ： admin@wise2c.com
* passworkd ： wise2c2017


## troubleshooting
you can check service health by consul ：
```
< HOST > : 8500
```
## Pipeline Stage

#### SCM
```
 -  git
 -  svn
```
   
#### BUILD 
```
 - maven
 - gradle
 - ant
 - golang
 ...
```
#### TEST
```
 - pybot
 - robot framework
 ...
```
#### BUILD IMAGE
```
 - build image
 - push  image
 ...
```
#### CHECK CODE
```
 - SonarQube
```
#### DEPLOY
```
 - k8s (upgrade or yaml)
 - ansible
 - rancher
 ...
```