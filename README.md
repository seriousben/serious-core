# serious-core

Core services for serious projects.

## Kustomizing

```
kustomize build overlay > manifests/kustomized-overlay.yaml
```

## Deploying

```
gcloud config set project projects-seriousben
gcloud auth application-default login
gcloud container clusters get-credentials main --region=us-east1

kubectl apply -f manifests
```