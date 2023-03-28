# stedi

These commands assume that redis and kafka are running locally on ports 6379 and 9092 respectively.

To start this project, run the following commands:

`docker build . -t stedi`

`docker run --env-file ./env.list stedi`

# Notes/Commands

kubectl get pods
kubectl describe pod <name>
kubectl logs <name>
kubectl apply -f dev.yaml
docker images
docker run -p port#:port#
docker ps
docker kill <name>

# Final Requirements

redis.yaml file
dev.yaml file
gcr.io-image in Google Cloud
Dockerfile
Azure DevOps Pipeline
    - Docker build
    - Docker push
    - kubectl -deploy (like apply -f but scalable too)