# Springboot Kubernetes Application

We will create a simple springboot hello world server and deploy it to the our minikube cluster on the server.

## What have been done?
 - Made an example springboot application using maven.
 - Installed a minikube local cluster on the remote machine ( tezcan.dev )
 - Made a docker image using mvwn spring-boot:build-image. 
 - Wrote a kubernetes.yml for pod and ingress deployments.
 - Installed a nginx service for reverse proxying minikube ingress.
 - Configured ssl for secure comminication.
 - Installed a Jenkins node and the frontend on the same server.
 - Created a freestyle project to control kubernetes.
 - Configured when there is a push or pr request in Github trigger pipeline via Github Webhooks.
 - Jenkins pulls the repository rebuilds the docker image and publishes over de kubernetes.
 
 ## Links
 Live url : https://tezcan.dev/
 
 Jenkins: http://tezcan.dev:8080/
 Credentials:
- guest:guest