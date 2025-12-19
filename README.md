🚀 End-to-End CI/CD Pipeline using Jenkins, Docker & Kubernetes (kind)

This project demonstrates a complete end-to-end CI/CD pipeline using Jenkins, where a sample Netflix-style frontend application is automatically built, containerized, and deployed to Kubernetes (kind).

The goal of this project is to practically demonstrate CI/CD concepts, not just theory.

📌 High-Level Architecture
GitHub (Source Code)
        |
        v
     Jenkins
        |
        |-- Build Docker Image
        |-- Load Image into kind
        |-- Deploy to Kubernetes
        v
Kubernetes (kind Cluster)
        |
        v
  Netflix Clone App 
