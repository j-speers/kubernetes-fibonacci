# Kubernetes Fibonacci

This repository demonstrates a Fibonacci number generator running in a Kubernetes cluster. It includes deployment configurations for both the application and its associated services, showing how to scale and manage a simple application in Kubernetes.

## Features

- **Fibonacci API**: A web service that computes Fibonacci numbers.
- **Kubernetes Deployment**: YAML configurations to deploy the service in a Kubernetes cluster.
- **Horizontal Scaling**: Example of scaling the Fibonacci service using Kubernetes.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/j-speers/kubernetes-fibonacci.git
2: Deploy the app:
   ```bash
   kubectl apply -f deployment.yaml
