# Horde Kubernetes Deployment

## Prereq

### Create Namespace

### Register github registry credentials with namespace

- Create and save a Github Personal Access Token with read:packages permission
- run ```kubectl create secret docker-registry horde-ghcr-pull --docker-server=https://ghcr.io/ --docker-username=anything --docker-password=<YOUR_GHCR_PAT>```

### Have an ingress controller



### Apply deployment

### Apply service

### Apply Ingress
