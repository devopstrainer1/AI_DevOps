# Kubernetes

## What is Kubernetes?
Kubernetes is an open-source platform for automating deployment, scaling, and management of containerized applications.

## Architecture
- Master Node: Controls and manages the cluster.
- Worker Nodes: Run containerized applications.
- etcd: Key-value store for cluster data.
- Kubelet: Agent running on each node.

## Example Manifest
```yaml
apiVersion: v1
kind: Pod
metadata:
  name: nginx
spec:
  containers:
    - name: nginx
      image: nginx
```
