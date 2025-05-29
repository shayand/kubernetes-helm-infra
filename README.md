# Kubernetes Cluster Setup and Tools

This repository contains various components and configurations for setting up and managing a Kubernetes cluster and its associated tools. The structure is modular, with each subdirectory representing a specific tool or configuration.

---

## Directory Structure

### `argocd/`
Contains configuration files for deploying and managing [Argo CD](https://argo-cd.readthedocs.io/), a declarative GitOps continuous delivery tool for Kubernetes.

### `calico/`
Includes manifests and configurations for setting up [Calico](https://www.projectcalico.org/), a networking and network security solution for Kubernetes.

### `dashboard/`
Contains the Kubernetes Dashboard manifests, providing a web-based UI for managing Kubernetes resources.

### `.git/`
Standard Git metadata directory used for version control.

### `gitlab/`
Houses the Helm charts or manifests to deploy [GitLab](https://about.gitlab.com/) on Kubernetes. This setup may include runners, registries, and integration with Argo CD or Harbor.

### `harbor/`
Includes Helm charts or Kubernetes manifests to deploy [Harbor](https://goharbor.io/), a cloud-native container registry that secures artifacts with policies and role-based access control.

### `helloworld/`
Example or test application (likely a simple containerized web service) used to validate deployment pipelines or ingress rules.

### `ingress/`
Configuration for setting up an [Ingress Controller](https://kubernetes.io/docs/concepts/services-networking/ingress-controllers/) (e.g., NGINX), including ingress resources for routing traffic to services.

### `LICENSE`
Contains the license for the project. Review it to understand the usage rights and restrictions.

### `minio/`
Deployment files for [MinIO](https://min.io/), an S3-compatible object storage solution for Kubernetes environments.

### `minio-deprecated/`
Older or deprecated configuration files for MinIO. May be kept for reference or rollback purposes.

### `monitoring/`
Monitoring stack configurations, possibly including [Prometheus](https://prometheus.io/), [Grafana](https://grafana.com/), [Alertmanager](https://prometheus.io/docs/alerting/alertmanager/), etc.

### `postgres/`
Manifests or Helm charts to deploy a [PostgreSQL](https://www.postgresql.org/) database instance.

### `provisioner/`
Includes configuration for Kubernetes storage provisioning (e.g., StorageClasses, dynamic provisioners, or external provisioners like NFS or CSI drivers).

### `website/`
Contains static files, manifests, or Helm charts for deploying a web frontend or documentation site related to the project.

---

## Getting Started

Each subdirectory typically includes a `README.md` or deployment guide to help with setup and usage. Make sure your Kubernetes cluster is running and has sufficient permissions and resources.

1. Clone this repo
2. Navigate to the desired tool's directory
3. Apply the Kubernetes manifests or install via Helm

---

## License

This project is licensed under the terms defined in the [LICENSE](./LICENSE) file.
