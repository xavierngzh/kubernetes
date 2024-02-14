# Overview

Kubernetes is an open-source container orchestration platform that automates the deployment, scaling, and management of containerized applications. It provides a flexible and scalable infrastructure for deploying, managing, and scaling applications seamlessly across clusters of servers.

Nana Janashia's Kubernetes Tutorial (https://youtu.be/s_o8dwzRlu4?feature=shared) covers all the core concepts, including the main Kubernetes components that we need to learn to work efficiently with Kubernetes. I've learnt the syntax and contents of K8s configuration file , which is used to create and configure components in a Kubernetes cluster as well as how to setup a K8s cluster locally with minikube. There is also a hands-on demo project, where we get to learn how to deploy a web application with its database into a local Kubernetes cluster. It's a simple but realistic application setup, which can also serve as a blueprint configuration for most common application setups. 

These are the steps of the project:

1. Create MongoDB ConfigMap
2. Create MongoDB Secret
3. Create MongoDB Deployment and Service
4. Create WebApp Deployment and Service
5. Pass Secret Data to MongoDB Deployment
6. Pass Config Data to WebApp Deployment
7. Configure External Access
8. Deploy all K8s resources into Minikube cluster
9. Interacting with Kubernetes Cluster
10. Access Web Application in Browser
