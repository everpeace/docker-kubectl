[![Docker Build Status](https://img.shields.io/docker/build/everpeace/kubectl.svg)](https://hub.docker.com/r/everpeace/kubectl/)[![ImageLayers Size](https://img.shields.io/imagelayers/image-size/everpeace/kubectl/latest.svg)](https://hub.docker.com/r/everpeace/kubectl/)

# docker-kubectl
Alpine based thin docker image for just doing `kubectl` command.

```
$ kubectl run  -it --rm --restart='Never' --image=everpeace/kubectl:latest po-kubectl -- kubectl cluster-info
Kubernetes master is running at https://10.96.0.1:443

To further debug and diagnose cluster problems, use 'kubectl cluster-info dump'.
```

## versions
- `everpeace/kubectl:1.9.2`
- `everpeace/kubectl:1.9.4`

