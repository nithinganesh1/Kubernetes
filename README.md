
# Kubernetes

## Basics
k8s is a most popular container orchestration tool. 

Kubernetes is a tool that helps us to run and manage application in conainers. 

Developed by Google Lab in 2014 also know as k8s.

it is an open-source container orchestraction platform that automates the deployment, management, and scaling of container-based applications in diffrent kinds of environmnets like physical virtual and cloud-native computing fundations

containers are isolated from each other so that multiple containers can run on the same machine without interruting anyone else.

How to manage containers effectively
eg. a sheep captain for these containers

## history
created by google BORG to manage their linux containers, in mid-2014, kubernets realsed as an open source version of borg

Now managed by CNCF(Cloud Native Computing Foundation)

## Benefits
1. Automated deployment and management
2. Scalability
3. High availablity
    * High availablity for our application
    * reduce the latency isssues for the end users
4. Cost-effectiveness
    * reduce unnecessary use of infra 
5. Improved developers productivity

## Ohter Container Orchestration platform
1. Docker Swarm
2. OpenShift
3. Nomad

## Features of Kubernetes
1. Automated Scheduling / service discovery and load balancing
2. Self-Healing Capabilities
    * rescheduling, replacing and restarting the containers that are dead
3. Automated Rollouts and Rollbacks
4. Horizontal Scaling and Load Balancing
    * scale up and down the application as per the requirements
5. Best Resource Utilization
6. Seacreat and configuration management
7. Community Support
__________________________________
### Master node (control plane), Worker nodes

1. Master node 4 primery service in master node
   * Api Server
   * Scheduler
   * Controller manager
   * etcd
2. Worker node
   * kubelet
   * proxy
   * docker engine
  
