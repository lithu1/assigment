# 1.
## What is the difference between a Pod, Deployment, and Service in Kubernetes?

### Pod  
- It is the smallest deployment unit.  
- It can contain one or more containers in the same network.  
- If a Pod dies in Kubernetes, a new Pod can be created but with a different IP.  

### Deployment  
- Deployment is like a manager that controls all the Pods.  
- It makes sure the right number of Pods are running.  
- If a Pod crashes, it creates a new Pod.  
- It can also roll back to the old version.  

### Service  
- It is used to expose the Pod to the outside world.  
- It provides load balancing.  
- Even if a Pod dies and comes back with a new IP, we can still access it using labels and selectors.  
## Why do we need EKS (or managed Kubernetes) instead of running Kubernetes on VMs?

In case of Kubernetes on VMs, we have to manage everything like installation, upgrades, scaling, and security.  
In EKS, AWS takes care of all these, and we only manage the worker nodes and our applications.
# 2.
- Completed writing Kubernetes YAML file for deploying app from Part-2 and a LoadBalancer service for it in flask-app-deployment.yaml.
