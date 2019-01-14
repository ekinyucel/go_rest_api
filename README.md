# Go Rest API - CI/CD
Intention of this project is to create a Jenkins pipeline for GO rest API project. API is being deployed on Digitalocean server. 
Whenever a new commit is pushed to this repository, jenkins on the server is automatically fetched the code and deploying a container on the server

# How to build
```
$ docker build -t go_rest .
$ docker run -p 9090:3030 -t go_rest
```

# Automatic deployment
Settings can be found inside the Jenkinsfile

# Stack

- Go 1.10
- Docker
- Jenkins
- Digitalocean