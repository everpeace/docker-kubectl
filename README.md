# docker-kubectl
Alpine based thin docker image for just doing `kubectl` command.

```
$ kubectl run --rm --restart='Never' everpeace/kubectl:latest po-kubectl -- kubectl cluster-info
```
