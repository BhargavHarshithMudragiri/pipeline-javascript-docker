# Sample Docker and Kubernetes Node.JS app

This code sample uses the Node.js web framework Express to create a basic web server that listens for HTTP requests on port 8080.

The code includes a Dockerfile in `app/Dockerfile`, which includes the steps to build a container image that can run a Node.js web server. The code sample also includes `deployment.yml` and `service.yml`. `deployment.yml` describe how to deploy the containerized Node.JS application to a Kubernetes cluster. `service.yml` creates a service and a secret resource.
