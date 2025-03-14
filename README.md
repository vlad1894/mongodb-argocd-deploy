# deploying MongoDB with ArgoCD & Kustomize

This repository contains a setup for deploying MongoDB in a Kubernetes cluster using ArgoCD and Kustomize. The goal is to manage MongoDB declaratively through Git while keeping the configuration modular with Kustomize.


Requirements
	•	A Kubernetes cluster
	•	ArgoCD installed and running
	•	A Git repository for storing manifests
	•	SSH access set up for ArgoCD to pull from the repository

 
