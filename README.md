# k8s-notes
 my k8s notes

# Layers of Abstraction
- Deployment manages a...
- Replicaset manages a...
- Pod is an abstraction of container
# CRUD
Available components:
- deployment
- replicaset
- pod
## CRUDS
- Get - kubectl get [component] // returns all pods
- Create - kubectl create [component] [name]
- Edit - kubectl edit [component] [name]

# Status of different K8s components
- Debugging Pods - kubectl logs [Pod Name]