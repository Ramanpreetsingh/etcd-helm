# etcd-helm
This chart bootstraps a etcd deployment on a Kubernetes cluster using the Helm package manager.

Default config: This chart creates a new namespace, installs a etcd stateful set with 3 replicas backed by 3 separate persistent volumes.

Run a local k8s cluster on local with minikube:

```minikube start```

```minikube dashboard```

Install helm chart from etcd-helm directory:

```helm install <release-name> ../etcd-helm/```
  
Upgrade helm chart from etcd-helm directory:

```helm upgrade <release-name> ../etcd-helm```
