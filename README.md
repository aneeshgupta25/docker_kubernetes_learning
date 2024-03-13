# NodeJS App with Docker and Kubernetes
This project is aimed at testing a NodeJS application that appends text sent by the user to a file stored in the local file system. The purpose of this project is to learn and test Docker and Kubernetes features. For local Kubernetes orchestration, Minikube has been utilized.

## Features
- __NodeJS App__: A simple NodeJS application that accepts text input from users and appends it to a file.
- __Docker Integration__: Docker has been used to containerize the NodeJS application for easy deployment and management.
- __Kubernetes Orchestration__: Kubernetes is used to orchestrate the Docker containers. Minikube, a lightweight Kubernetes implementation, is employed for local development and testing.
- __Data Persistence__: To ensure data persistence within the Kubernetes environment, various techniques such as hostPath and persistent volume claims have been explored.

## Data Persistency
In the single-node environment provided by Minikube, hostPath is used for data persistence. Although Minikube offers a single-node setup, concepts like persistent volume claims are utilized for learning purposes and to ensure compatibility with multi-node environments.
