# Kubernetes Projects

A collection of hands-on Kubernetes and cloud-native projects created for learning, experimentation, and developing practical DevOps skills.

The repository contains practical exercises covering Kubernetes, Helm, monitoring, networking, storage, security, and cloud deployments.

## Projects

### Grafana Lab

A hands-on Kubernetes monitoring project using:

* Kubernetes
* Minikube
* Helm
* Grafana
* PostgreSQL
* NGINX Ingress
* PersistentVolumes and PersistentVolumeClaims
* Kubernetes Secrets

The project demonstrates how Grafana and PostgreSQL can be deployed on Kubernetes and how application data and configuration persist across Pod restarts.

[Open Grafana Lab](./grafana-lab/)

## Topics

The repository will gradually cover:

* Kubernetes fundamentals
* Pods, Deployments and ReplicaSets
* Services and networking
* Ingress
* PersistentVolumes and PersistentVolumeClaims
* ConfigMaps and Secrets
* Helm
* Monitoring and observability
* Grafana and Prometheus
* Kubernetes security
* AWS EKS
* CI/CD
* Infrastructure as Code

## Environment

The projects are primarily developed and tested using:

* Ubuntu Linux
* Docker
* Minikube
* Kubernetes
* Helm
* AWS

## Repository Structure

```text
kubernetes-projects/
│
├── README.md
│
├── grafana-lab/
│   ├── grafana/
│   ├── postgres/
│   ├── helm-learning/
│   └── namespaces/
│
└── future-projects/
```

## Goal

The goal of this repository is to build practical Kubernetes knowledge through hands-on projects and document the lessons learned along the way.

Each project will contain its own documentation, configuration files, deployment manifests, and troubleshooting notes.

## Disclaimer

These projects are primarily intended for learning and experimentation. Some configurations may be simplified compared with production Kubernetes environments.
