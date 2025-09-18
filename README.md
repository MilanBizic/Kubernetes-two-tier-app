# Kubernetes-two-tier-app
A simple two-tier web application (Python/Flask) deployed on a local Kubernetes cluster to demonstrate core concepts
![Application Screenshot](https://github.com/MilanBizic/Kubernetes-two-tier-app/blob/main/1.png?raw=true)
This repository contains a complete, containerized two-tier web application designed to showcase a full development-to-deployment workflow on Kubernetes. A Python Flask frontend dynamically fetches data from a backend API by resolving its internal service name, demonstrating a core microservice communication pattern.
![Application Screenshot](https://github.com/MilanBizic/Kubernetes-two-tier-app/blob/main/2.png?raw=true)
The image displays the terminal workflow for building the application's microservices into container images using Docker. After successfully building the backend image, the same process is initiated for the frontend, preparing all necessary components for deployment to the Kubernetes cluster.
![Application Screenshot]( https://github.com/MilanBizic/Kubernetes-two-tier-app/blob/main/3.png?raw=true) 
The docker images command displays the final artifacts from the project's containerization phase. This output confirms both the backend-app and frontend-app images were successfully built and tagged, making them available for the Kubernetes cluster to pull and run as pods.
![Application Screenshot](https://github.com/MilanBizic/Kubernetes-two-tier-app/blob/main/4.png?raw=true) 
As a crucial setup step before deployment, this command directs the kubectl CLI to communicate with the docker-desktop Kubernetes cluster. This ensures the application's resources are created in the same environment where the container images are available.



 
 





