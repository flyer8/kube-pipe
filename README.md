## Usage Jenkinsfile (groovy pipeline) for deploying webapp (nginx server) in Kubernetes using Helm package manager

Jenkins has been deployed accoding to https://github.com/GoogleCloudPlatform/continuous-deployment-on-kubernetes

For Helm deploying, Docker image https://hub.docker.com/r/guigo2k/jenkins-k8s-slave/ is used for dynamical Jenkins slave nodes.
Intended to be used as a replacement for gcr.io/cloud-solutions-images/jenkins-k8s-slave in continuous-deployment-on-kubernetes.

Jenkins server URL: http://35.190.51.64/

login: jenkins

password: admin

Docker image of Nginx-lua server.
https://hub.docker.com/r/flyer8/nginx-lua/

Nginx-lua webapp URL: http://35.190.134.89/
