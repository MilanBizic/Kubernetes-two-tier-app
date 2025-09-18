# Kubernetes-two-tier-app
A simple two-tier web application (Python/Flask) deployed on a local Kubernetes cluster to demonstrate core concepts
![Application Screenshot](https://github.com/MilanBizic/Kubernetes-two-tier-app/blob/main/1.png?raw=true)
This repository contains a complete, containerized two-tier web application designed to showcase a full development-to-deployment workflow on Kubernetes. A Python Flask frontend dynamically fetches data from a backend API by resolving its internal service name, demonstrating a core microservice communication pattern.
![Application Screenshot](https://github.com/MilanBizic/Kubernetes-two-tier-app/blob/main/2.png?raw=true)
The image displays the terminal workflow for building the application's microservices into container images using Docker. After successfully building the backend image, the same process is initiated for the frontend, preparing all necessary components for deployment to the Kubernetes cluster.







