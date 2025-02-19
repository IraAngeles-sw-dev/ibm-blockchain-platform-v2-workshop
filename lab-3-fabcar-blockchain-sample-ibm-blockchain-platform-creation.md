---
description: >-
  Create IBM Blockchain Platform service, deploy in Kubernetes cluster, start
  IBM Blockchain Platform console
---

# Lab 3: FabCar Blockchain Sample - IBM Blockchain Platform Creation

### Kubernetes cluster 

* Get kubernetes namespace

```text
kubectl get namespace
```

* Get kubernetes pods

```text
kubectl get pods -n <IBP namespace> -w
```

### Create IBM Blockchain Platform service

* Create the [IBM Blockchain Platform](https://console.bluemix.net/catalog/services/blockchain/) service on the IBM Cloud \(Region - Dallas\). You can find the service in the `Catalog`, and give a name.

![](./assets/sc1.gif)

* After your kubernetes cluster is up and running, you can deploy your IBM Blockchain Platform on the cluster. The service walks through few steps and finds your cluster on the IBM Cloud to deploy the service on.

![](./assets/sc2.gif)

* Once the Blockchain Platform is deployed on the Kubernetes cluster, you can launch the console to start operating on your blockchain network.

![](./assets/sc3%20%281%29.gif)

* Start IBM Blockchain Platform Console

![IBM Blockchain Platform Console](./assets/sc4.gif)

