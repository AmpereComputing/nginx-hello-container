# Deploy Hello World WebApp container to OCI OKE 

The steps to deploy Hello World WebApp container with PVC to OCI

% kubectl create -f nginx-hello-app-pvc.yaml 

% kubectl create -f nginx-hello-app-deployment.yaml 

% kubectl create -f nginx-hello-app-service.yaml 

The step to deploy the StatefulSet of Nginx Front App container with PVC template to OCI

% kubectl create -f nginx-front-app.yaml
