# GitOps with FluxCD and Tanzu Packages

This repo can be used to deploy Tanzu Packages in a GitOps fashion. Read the following blog post for instructions on how to use the repo and its content:

https://beyondelastic.com/2022/06/08/gitops-with-fluxcd-and-tanzu-packages/

![alt text](https://github.com/beyondelastic/gitops-tanzu-packages/blob/main/images/overview.png)

Please be aware, that this repo is not officially verified, tested or supported by VMware!

Note: Packages in this repository are pre-configured with example values for custom virtual hosts (ingress), storage class, passwords, syslog target, etc… you have to change the configuration according to your environment first! 

The FluxCD Kustomization manifests have the following dependencies configured:
![alt text](https://github.com/beyondelastic/gitops-tanzu-packages/blob/main/images/dependencies.png)