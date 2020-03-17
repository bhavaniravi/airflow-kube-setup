# Airflow Kubernetes Setup

## Create Docker Image

```
cd scripts/docker
docker build -t airflow .
```

> Push the image to your favorite registry and get the URL

## Deploy in kubernetes

1. Find $IMAGE in the repository
2. Change it with the repository URL

```
cd scripts/
./kube/deploy.sh -d persistent_mode
```
The other supported modes is `git_mode`

## Walkthrough blog

Coming soon!