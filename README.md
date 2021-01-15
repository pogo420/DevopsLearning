# DevopsLearning
Repo for all personal devops knowledge 
Check this [link](https://github.com/pogo420/DevopsLearning/wiki) for learning documents.

## Jenkins Startup:
`docker run -d -p 8080:8080 -p 50000:50000 -v jenkins_home:/var/jenkins_home jenkins/jenkins:latest`
* 8080 -> User interface
* 50000 -> Jenkins master slave.

## Minikube Startup:
### First time
minikube start --vm-driver=virtualbox
### Next time
minikube start
### Delete cluster
minikube delete
### status
minimuke status
