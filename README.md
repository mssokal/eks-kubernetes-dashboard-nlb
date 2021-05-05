# Kubernetes Dashboard behind AWS Network Load Balancer

This is a simple manifest to allow accessing Kubernetes Dashboard through NLB. This is currently using NGINX Ingress Crontroller.

Assuming you already have the EKS Cluster up'n running:

Instructions to install NGINX Ingress Controller on EKLS can be found here
- https://kubernetes.github.io/ingress-nginx/deploy/#aws

Instructions to install the metrics-server on EKS
- https://docs.aws.amazon.com/eks/latest/userguide/dashboard-tutorial.html

Instructions to install Kubernetes Dashboard on EKS
- https://docs.aws.amazon.com/eks/latest/userguide/dashboard-tutorial.html

