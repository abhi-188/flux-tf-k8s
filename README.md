# GitOps Terraform EC2 with KubeVela

This repository contains the complete configuration for provisioning an EC2 instance with a Load Balancer using GitOps with Flux and Terraform.

## Structure

- `clusters/dev/` – Contains the Flux configurations.
- `terraform/` – Contains the Terraform configuration files.

## Installation

- Install Flux in your Kubernetes cluster.
- Deploy the Terraform resources with:
```bash
kubectl apply -f terraform/ec2.yaml -n terraform