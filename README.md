1. Run `docker image build --tag=golovchen.com:latest .`
2. Run `docker container run --name golovchen.com --detach --publish 8080:80 golovchen.com:latest`
3. Visit http://localhost:8080
