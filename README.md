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

# Debugging pods
- Pod Logs - kubectl logs [pod_name]
- Get Interactive Terminal - kubectl exec -it [pod_name] -- bin/bash
- Get Info About Pod - kubectl describe pod [pod_name]
# Use Config File
- Apply a config file - kubectl apply -f [file_name]
- Delete a config file - kubectl delete -f [file_name]
