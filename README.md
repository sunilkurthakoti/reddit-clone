# reddit-clone

### Reddit Clone k8s Ingress

This project implements a well-structured approach to automate the delivery of a highly scalable Reddit clone application using a CI/CD pipeline with Docker, Docker Hub, and Kubernetes Minikube. Here's a detailed breakdown of the key components:

#### CI/CD Pipeline Setup:
- Designed and implemented a robust CI/CD pipeline to automate the delivery process from code changes to deployment.
- Integrated Docker, Docker Hub, and Kubernetes Minikube technologies into the pipeline.

#### Continuous Integration (CI):
- Set up an automated pipeline to integrate code changes from the development team.
- Ensured code changes are thoroughly tested before pushing updated container images to Docker Hub.

#### Continuous Deployment (CD):
- Utilized Kubernetes Minikube for deploying container images to the appropriate environment based on test results.
- Designed the application to be highly available and scalable, leveraging Kubernetes features like services and ingress.

#### Performance Optimization:
- Implemented monitoring and logging functionalities to identify and troubleshoot any issues that may arise.
- Emphasized automation in the pipeline to minimize manual interventions and reduce human errors.

#### Key Technologies Used:
- Docker and Docker Hub for containerization and image management.
- Kubernetes and Minikube for container orchestration and deployment.
- CI/CD practices for automating the software delivery process.
- Monitoring and logging tools to ensure optimal performance and reliability.

### Project Overview:
- **Project Description**: Automating the Delivery of Highly Scalable Reddit Clone Application using CI/CD Pipeline with Docker, Docker Hub, and Kubernetes Minikube.

#### CI/CD Pipeline Steps:
1. **Clone the Source Code**:
   - Clone the GitHub repository for the Reddit clone application.
  
2. **Containerize the Application using Docker**:
   - Write a Dockerfile to containerize the application and build a Docker image.
  
3. **Push the Image To DockerHub**:
   - Push the Docker image to DockerHub for deployment.
  
4. **Write Kubernetes Manifest Files**:
   - Create Deployment and Service YAML files for the application.
   - Deploy the application to Kubernetes and create a service for it.
  
5. **Configure Ingress**:
   - Write an Ingress YAML file to route external traffic to the Kubernetes endpoints.
   - Enable Ingress on Minikube.
   - Apply the Ingress settings.
  
6. **Expose the App**:
   - Expose the deployment and app service.
   - Test the deployment and Ingress.

#### Prometheus and Grafana Setup:
1. **Add Helm Repositories**:
   - Add Helm repositories for Prometheus and Grafana charts.
  
2. **Install Prometheus**:
   - Create a namespace for Prometheus.
   - Install Prometheus using Helm.
  
3. **Edit Prometheus and Grafana Services**:
   - Edit the Prometheus and Grafana services to change the type to LoadBalancer.
  
4. **Access Grafana Dashboard**:
   - Use the provided credentials to access the Grafana dashboard.
   - Configure Grafana to monitor the cluster.
  
5. **Create a Dashboard in Grafana**:
   - Use the Grafana UI to import a dashboard using the provided dashboard ID.
   - Configure the data source to Prometheus.
   - Import the dashboard.
