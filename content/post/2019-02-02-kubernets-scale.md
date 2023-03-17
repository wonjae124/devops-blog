---
title: Scaling My Kubernetes Deployment
date: 2019-02-02
tags: ["kubernetes", "code"]
---

Scaling my kubernetes deployment

<!--more-->

```sh
    $ kubectl scale deployment/kubernetes-bootcamp --replicas=4
```

Now, check whether it is running:
```sh
    $ kubectl get deployments
    NAME                  Desired CURRENT UP-TO-DATE AVAILABLE AGE
    kubernetes-bootcamp   4       4       4          4         26s
    
    $ kubectl get pods -o wide
```
