![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/golovchen/golovchen.com)

[Docker hub](https://hub.docker.com/r/golovchen/golovchen.com)

1. Run `docker image build --tag=golovchen.com:latest .`
2. Run `docker container run --name golovchen.com --detach --publish 80:80 golovchen.com:latest`
3. Visit http://localhost

### With Kubernetes
1. Run `docker image build --tag=golovchen.com:latest .`
1. Run `kubectl apply --filename kubernetes.yaml`
2. Visit http://localhost:30001
