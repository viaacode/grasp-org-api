# grasp-org-api
Grasp config for Organizations API
## update configmap for grasp
updates the configmaps which hold the configuration for org api

## Run locally with docker

Make sure you have a `services.json` that configures your SPARQL endpoint.

```
docker-compose up
```

## Update version

```
git checkout main
git tag -a vX.X.X
git push --tags
```
