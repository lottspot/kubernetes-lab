# Kubernetes Lab

This repository provides some resources which are useful for experimenting
with kubernetes. It only provides API resources and does not provide any
utilities for deploying kubernetes or storage infrastructure.

Deploying resources defined in this repository is as simple as running
```
kubectl create -f path-to/resource.yml
```
It would be advisable to create Persistent Volume and Persistent Volume Claim
resources before creating Deployments, as Deployments may need to utilize those.
