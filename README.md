# Docker Compose Slurm Cluster

A testbed repo to make a local slurm cluster, for testing HPC applications, 
through docker-compose. 

Initial idea from https://medium.com/analytics-vidhya/slurm-cluster-with-docker-9f242deee601

## Instructions

From the root of this repo simply run 
```
docker-compose up -d
```

This will start a jupyter-session on localhost:8888 which you can use to access 
the cluster, write code and execute things via the spun-up slurm cluster.  