## **Base Layer: OpenStack Nodes on CloudLab**
The base layer involves setting up OpenStack nodes on CloudLab, providing the infrastructure for running the Kubernetes cluster. OpenStack is used as the underlying cloud platform to manage the virtualized resources.

- Provisioning OpenStack nodes on CloudLab
- Setting up networking, storage, and compute resources through OpenStack

## **Kubernetes Layer: Kubespray on Top of OpenStack**
Once the OpenStack nodes are provisioned, the next step is to deploy a Kubernetes cluster using Kubespray, a robust tool for Kubernetes cluster provisioning. Terraform is used to automate the deployment and infrastructure management process.

- Deployment of Kubernetes using Kubespray on the OpenStack infrastructure
- Automated infrastructure management with Terraform
- High availability and scalable cluster setup

