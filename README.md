# nginx-hello-container
A rootless Nginx Hello Web App Container 

## Building locally
Building this image requires Docker 17.05 or higher, Podman 3.3 or above. Given that you have all the required dependencies, building the image is as simple as running a docker build:

```
docker build -t ampere/nginx-front-app .
```
or
```
podman build -t ampere/nginx-front-app .
```
