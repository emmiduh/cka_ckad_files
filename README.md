# CKA/CKAD Configuration Files

This repository contains Kubernetes configuration files I created for various use cases related to **CKA** (Certified Kubernetes Administrator) and **CKAD** (Certified Kubernetes Application Developer). These files are examples of YAML configurations used to deploy various Kubernetes resources, including deployments, services, daemonsets, jobs, cronjobs, configmaps, secrets, and more, and are a aprt of my code-along engagements while advancing my knowledge of kubernetes.

## Prerequisites

Ensure that you have a kubernetes cluster made up of at least one worker node and a master node, and the following installed:

- [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/) (Kubernetes CLI)
- [Kubernetes cluster](https://kubernetes.io/docs/setup/)
- [Helm](https://helm.sh/) (if applicable)

## How to Use

1. **Deploy Resources to Kubernetes:**

   You can apply any of the YAML files to your Kubernetes cluster using `kubectl apply -f <file_name>.yaml`.

   Example:
   ```bash
   kubectl apply -f 01_deployment.yaml

2. **Inspect Resources:**
    kubectl get deployments
    kubectl get services
    kubectl get pods


3. **Delete Resources:**
    kubectl delete -f <file_name>.yaml
