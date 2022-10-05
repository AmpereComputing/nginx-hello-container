# Deploy this Hello World WebApp container to SUSE K3s cluster

## The steps to deploy Hello World WebApp container with PVC to K3s + Longhorn 
It's a single pod only.

% kubectl create -f nginx-hello-app-pvc.yaml 

% kubectl create -f nginx-hello-app-deployment.yaml 

% kubectl create -f nginx-hello-app-service.yaml 

Please make sure there is a FQDN in the ingress YAML file for the container 

% kubectl create -f nginx-hello-app-ingress.yaml 

## The following is deploying a StatefulSet of Nginx Webserver container 
It's a StatefutSet with 3 replicas (by default) with PVC tempate to K3s with Longhorn. 

% kubectl create -f nginx-front-app.yaml 
