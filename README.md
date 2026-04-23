This project demonstrates the deployment of a scalable and highly available three-tier web application on Amazon Elastic Kubernetes Service using Amazon Web Services. The architecture is divided into presentation, application, and database layers, following modern cloud-native design principles.

The application is containerized and orchestrated using Kubernetes, enabling efficient resource management, auto-scaling, and high availability. The frontend (presentation layer) handles user interactions, while the backend (application layer) processes business logic and communicates with the database layer for data storage and retrieval.

An Application Load Balancer is used to distribute incoming traffic across multiple pods, ensuring fault tolerance and seamless scaling. The infrastructure is deployed within a secure network environment, leveraging AWS networking capabilities for isolation and controlled access.

The deployment emphasizes DevOps best practices such as containerization, orchestration, and automated scaling. It also supports rolling updates and self-healing features provided by Kubernetes, ensuring minimal downtime and improved reliability.

This project highlights the use of managed Kubernetes services to simplify cluster management while maintaining flexibility and control over application deployments. It serves as a practical example of running production-ready, cloud-native applications on AWS using a three-tier architecture.
