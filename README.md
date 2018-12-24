# simple-k8s

This is a simple project containing a couple of configuration files to be able to create and run a PoD in Kubernets.

## Creating a Pod in Kubernets
The images used in the configuration files are hosted at Docker Hub and were created previously, so you have to issue
the following commands using the `kubectl` tool in order to create a POD

```
kubectl apply -f client-pod.yaml
kubectl apply -f client-node-port.yaml
```
