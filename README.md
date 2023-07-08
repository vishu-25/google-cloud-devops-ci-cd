# Google Cloud Platform DevOps Project
<h1>Introduction</h1>

- In this project we will be dockerizing a simple Flask-based web-application and build a CI-CD pipeline on Google Cloud Platform using CodeBuild, which gets triggered on detecting any commits on [main](https://github.com/vishu-25/google-cloud-devops-ci-cd.git) branch of the GitHub repository. 
- The CloudBuild pipeline will build and store the Docker image to GCP Artifact Registry, 
- The CloudBuild pipeline will then obtain the ltest Docker image from GCP Artifact Registry and deploy it on Google Kubernetes Engine. 

## Tools used in the Project
1. [Git](https://git-scm.com/doc)
2. [GitHub](https://docs.github.com/en)
3. [Google Cloud Platform](https://cloud.google.com/docs) <br>
   a. CloudBuild <br>
   b. GCP Artifact Registry <br>
   c. Google Kubernetes Engine <br>
4. [Docker](https://docs.docker.com/)
5. [Kubernetes](https://kubernetes.io/docs/home/)



## CI-CD Pipeline Plan

![CI-CD-Diagram](images/gcp-ci-cd-diagram.png)

