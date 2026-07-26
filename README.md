# k8s-gitops-app
Application repo for the GitOps demo. The pipeline builds and pushes the Docker image,
then updates the image tag in k8s-gitops-manifests. ArgoCD handles the deployment.
