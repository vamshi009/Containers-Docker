# Containers-Docker
Concepts for Containers, Docker, Kubernetes, Micro Services

file -> Image (Read only) --> Container(Read/Write)

The Image is built layer by layer with the commands in the readme file.

A Virtual machine has an OS of its own, whereas the Container runs upon a Container Engine which takes care of OS, allocation of resources etc.

Kubernetes arch -> Cloud manager, Kube manager, Kubectl, kube API manager, etcd (Key- value store), Kube proxy, Node
Kuberantes Objects -> Pods, Replica sets and Deployment

Kn8 has imperative and declrative commands.

Declarative commands are more organised and help us keep track of the object Configuration across developers

Redhat Openshift combines Kn8 along with other tools that enhance developer experience.

Kubernates is part of wide  ecosystem.

Redhat Openshift:
  Builds:
    CI/CD
    Docker 
  Triggers:
    Webhooks 
    Image Changes
  Operators: 
      Custom Resource Definitions(CRD) + custom controllers
      
  IStio:
      Service Mesh: Connect + Observe + Control the connections between micorservices
