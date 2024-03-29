# OUTLINE

working copy, lots of stuff to shift around

## CONTAINERIZATION AND MICROSERVICES

Lectures around 'why containers', 'microservices', and modernization

Homework

* Phippy goes to the zoo (read) - https://azure.microsoft.com/mediahandler/files/resourcefiles/phippy-goes-to-the-zoo/Phippy%20Goes%20To%20The%20Zoo_MSFTonline.pdf
* Brendan Burns Video Series (watch)

Homework - none?

## INTRO TO DOCKER

Focus on docker containers, build and deploy

Materials - derive from https://www.oreilly.com/library/view/docker-containers-third/9780134862958/

Student Requirements:  attendees should be able to run docker in a VM or on local machine

Homework - hello world web .net core linux container running local and surfable

Topics

* Installing docker
* Docker registries
* Starting containers
* Making docker images from containers
* Building images
* Dockerfile tips

Homework - Standup image from docker as an AKS Container, call from postman or curl

## INTRO TO KUBERNETES

Topic

* Single node k8s
* Starting containers using k8s
* Deploying containers using yml
* Secrets
* Networking
* Deploying services to k8s

Homework - Deploy docker image into k8s

## INTRO TO AKS

Topics

* What is AKS?
* Create AKS Cluster
* Linux simple aks deploy - 
* Windows simple aks deploy - https://github.com/Azure/aks-engine/blob/master/docs/topics/windows.md - 

Materials sourcing

* https://github.com/Azure/kubernetes-hackfest

Student requirements - Access to Explorer Subscription / Portal in Azure

* Complete MS Learn on AKS - 6 modules 40 mins - send to lead mooc contacts - https://docs.microsoft.com/en-us/learn/modules/intro-to-azure-kubernetes-service/

Homework - AKS Workshop - https://aksworkshop.io/ (big homework)

## DEVOPS

* AzDevops - https://docs.microsoft.com/en-us/azure/devops-project/azure-devops-project-aks
* Helm

Suggested follow-on is AKS OpenHack onsite at custom location.

## BUILD, RUN

Focus on developer angles, the idea of running a microservice in a container.

* Project design and layout for k8s - https://info.microsoft.com/ww-OnDemandRegistration-successful-kubernetes-applications-webinar.html
* Authentication and authorization - https://docs.microsoft.com/en-us/azure/aks/operator-best-practices-identity  (maybe have this in tips)
* Dev and debug apps against an aks cluster - https://docs.microsoft.com/en-us/azure/aks/developer-best-practices-resource-management#develop-and-debug-applications-against-an-aks-cluster
* Build and run in various environments
  * Linux .NET Core
  * .NET Framework
  * Node.js web service and web
  * Python

## MONITORING / LOGGING AND STORAGE

* Storage and backup in AKS - https://docs.microsoft.com/en-us/azure/aks/operator-best-practices-storage

Container analytics, prometheus, other things

## DISTRIBUTED SYSTEMS

* Read the ebook from d50 course at d28-35
* Networking - Best practices for networking connectivity and security in aks - https://docs.microsoft.com/en-us/azure/aks/operator-best-practices-network
* Service mesh, consul or linker or istio
* pod security - https://docs.microsoft.com/en-us/azure/aks/developer-best-practices-pod-security

## DESIGN PRACTICES

* d50 materials
* aks reference archs
* docker files in k8s, other items
* When is PaaS a better fit?  When is containers a better fit?

## FINAL EXERCISE

AKS Openhack - live!!!!!

## TOPICS NOT COVERED

* Disaster recovery - https://docs.microsoft.com/en-us/azure/aks/operator-best-practices-multi-region
* Cluster isolation - https://docs.microsoft.com/en-us/azure/aks/operator-best-practices-cluster-isolation
* Cluster security and upgrades - https://docs.microsoft.com/en-us/azure/aks/operator-best-practices-cluster-security
* Container image and security - https://docs.microsoft.com/en-us/azure/aks/operator-best-practices-container-image-management
* Scheduler features - https://docs.microsoft.com/en-us/azure/aks/operator-best-practices-scheduler
