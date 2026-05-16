# Kubernetes Scheduling Cluster Dataset
This repository contains Kubernetes spec file for real world workload of an organization which serves multiple microservices over Kubernetes cluster. 
This dataset is divided into two sub dataset. Each represent cluster for different purpose.
1. Commons-cluster
This is smaller dataset used for non production microservice hosting. 
It has 8 Nodes with 8CPU cores and 16GB memory

2. Production cluster
This is larger dataset where multiple production microservices are hosted.
It has 42 nodes with different cpu and memory combinations, totalling around 324 CPU and 1327 GB memory.

Both dataset contains specification for nodes and scheduled pods in yaml and json description
