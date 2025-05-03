# K8s
Learning K8s

**Lecture 2:-**
Today i've learned about the K8s architecture.
it contains 2 planes:- 1. Control Plane 2. Data Plane

**Control plane has following components:-**
Master:- 
API Server - manages everything
etcd - it stores the key values/ data
scheduler - it actually schedules the work
controller manager - 
cloud controller manager(ccm) - it provides users flexibility to write their own logic asper their cloud provider. For on-prem - CCM is not required

**Data plane has following components:-**
Worker:- 
Kubelet - it manages the pods where actually container runs and it keeps monitoring if container is running or not
kubeproxy - it provides networking and load balancing to the pods/containers
container runtime - it is actailly responsible for running of the conatiners


**Lecture 3:-**
