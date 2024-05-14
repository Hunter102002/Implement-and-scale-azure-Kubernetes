# Implement and Scale Azure Kubernetes

## Objective

This project focused on deploying and managing a Kubernetes cluster using Azure Kubernetes Service (AKS). The tasks included setting up an AKS cluster, deploying a pod, scaling containerized workloads, and managing node pools. The main objective was to demonstrate the ability to orchestrate container deployment, scaling, and management using Kubernetes on Azure, providing a robust environment for developing, deploying, and managing containerized applications.


### Skills Learned

- AKS Cluster Setup: Learned to create and configure an AKS cluster, understanding the various configurations and settings to optimize for development and testing environments.
- Pod Deployment: Gained practical experience in deploying pods using Kubernetes commands, further understanding the container management processes.
- Workload Scaling: Developed skills in scaling applications within the AKS by adjusting the number of pods and nodes, demonstrating the dynamic scalability of containerized applications.
- Node Pool Management: Acquired knowledge on managing node pools in AKS, including scaling up the nodes and adjusting configurations to meet workload demands.
- Kubernetes Command-Line Tools: Enhanced proficiency with Kubernetes CLI tools such as kubectl for deploying, managing, and scaling containerized applications.

### Tools Used

- Azure Portal: Used for creating and managing AKS clusters and related Azure resources.
- Azure CLI: Utilized for interacting with Azure services, managing AKS clusters, and automating AKS configurations.
- kubectl: Essential tool for interacting with the Kubernetes cluster, managing deployments, and controlling the Kubernetes environment.
- Cloud Shell: Provided an integrated Bash interface in the Azure portal for managing Azure resources and Kubernetes commands directly.
- Monitoring Tools: Employed to monitor the performance and status of the Kubernetes cluster and its resources, ensuring optimal operation and troubleshooting issues.

## Steps
Create AKS Cluster
<img width="1470" alt="Screenshot 2024-05-13 at 11 39 58 PM" src="https://github.com/Hunter102002/Implement-and-scale-azure-Kubernetes/assets/98543129/9aa56948-de3e-4c6c-9d2e-ae09bb8386e9">

Open CLI and create a mounted storage account
<img width="794" alt="Screenshot 2024-05-13 at 11 41 42 PM" src="https://github.com/Hunter102002/Implement-and-scale-azure-Kubernetes/assets/98543129/79759908-346d-4f77-8907-c2bc651246e7">

Run these CLI prompts to deploy the Cluster
<img width="1249" alt="Screenshot 2024-05-13 at 11 44 29 PM" src="https://github.com/Hunter102002/Implement-and-scale-azure-Kubernetes/assets/98543129/194bacef-8499-4e66-b77d-db13c7f51c6c">


<img width="703" alt="Screenshot 2024-05-13 at 11 44 43 PM" src="https://github.com/Hunter102002/Implement-and-scale-azure-Kubernetes/assets/98543129/36b9b6ab-1900-4a86-9fd1-3f77e6c675bc">

Get the External IP Address

<img width="1071" alt="Screenshot 2024-05-13 at 11 45 30 PM" src="https://github.com/Hunter102002/Implement-and-scale-azure-Kubernetes/assets/98543129/9144ff4a-52a0-40c6-b917-509e118a21bd">


Verify Creation

<img width="992" alt="Screenshot 2024-05-13 at 11 48 05 PM" src="https://github.com/Hunter102002/Implement-and-scale-azure-Kubernetes/assets/98543129/1a1f4a94-76df-4372-bfae-d1d2624cc0cd">

Run Scale prompt in CLI

<img width="892" alt="Screenshot 2024-05-13 at 11 48 39 PM" src="https://github.com/Hunter102002/Implement-and-scale-azure-Kubernetes/assets/98543129/3b8ad231-c4ca-40a5-9d44-d64f4241f059">

In the portal create a scale node pool

<img width="583" alt="Screenshot 2024-05-13 at 11 49 40 PM" src="https://github.com/Hunter102002/Implement-and-scale-azure-Kubernetes/assets/98543129/80cead42-72b1-4865-9cb8-ea84fb605ade">

Scale through CLI 

<img width="1335" alt="Screenshot 2024-05-13 at 11 54 18 PM" src="https://github.com/Hunter102002/Implement-and-scale-azure-Kubernetes/assets/98543129/e95d5bf8-7815-4200-b156-903402b1a608">

<img width="914" alt="Screenshot 2024-05-13 at 11 55 04 PM" src="https://github.com/Hunter102002/Implement-and-scale-azure-Kubernetes/assets/98543129/cc23203f-e48f-4544-828c-75973e43bb3b">

Now delete

<img width="802" alt="Screenshot 2024-05-13 at 11 55 31 PM" src="https://github.com/Hunter102002/Implement-and-scale-azure-Kubernetes/assets/98543129/812f398e-5278-4861-b2c9-6300918ab091">
