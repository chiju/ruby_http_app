# Ruby HTTP Server

## Buliding docker file

For building docker file, execute ```docker build -t ruby_http_server:latest .``` from the ```docker``` folder

## Deploying HTTP app in kubernetes

For deployment, please execute ```kubectl create -f . ``` from the ```kuberenetes``` folder

## Pipeline

For pipeline, create a webhook in github so that any commit triggers a jenkins pipeline which deploys the app in kubernetes

## Architecture

- Deployement manifest has replicaset 
- Loadbalancer service for loadbalancing

