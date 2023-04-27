# Deploy Nginx Webserver container on Canonical MicroK8s cluster (v1.24)

The follwing is the step to deploy a StatefulSet of Nginx Webserver container on Canonical MicroK8s cluster
---
>It's a StatefutSet with 3 replicas (by default) with PVC template to MicroK8s cluster with the add-ons: Ingress, Metallb, OpenEBS MayaStor.
>
>Please make sure there is a FQDN in the ingress YAML file for the container!

% kubectl create ns vod-poc

% kubectl create -f nginx-front-app.yaml -n vod-poc
