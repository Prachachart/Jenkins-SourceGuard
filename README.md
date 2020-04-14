# Using the Check Point SourceGuard SAST Scanner in a Jenkins CICD Pipeline 

## Step by Step DevSecOps Tutorial to integrate in a Jenkins pipeline used to build a node.js app and deployed in a docker container, uploaded to a registry and in K8s cluster.

Node.js and other runtime apps can be packaged in a container image and deployed on Docker Hub or other registries. Devops teams are using
a CICD methodolgy to build this node.js using the code checked in a SCM branch as Git or Github in order to build and package into a container image to be stored on Docker Hub or any other registry and deployed in a Kubernetes cluster for runtime.
We will Github and Git as SCM or Source Code Management.

The app will be a simple node.js app
lets first provision the Jenkins server and I will be using jenkins on a ubuntu VM using Vbox
The vbox and vm can be provisioned automatically using a vagrant script located in my k8s training,
I chose to use VM as running jenkins in a docker container can be slow especially on macOs. 

Installation as follow:


