# Cloud Layer

## Core Topics
- **Identity & Access Management (IAM)**: Users, groups, roles, policies, least‑privilege principle.
- **Virtual Private Clouds (VPCs)**: Subnets, route tables, internet/NAT gateways, private networking.
- **Security Groups & Network ACLs**: Stateful firewalls, inbound/outbound rules.
- **Storage Permissions**: Bucket policies, object ACLs, encryption at rest.
- **Load Balancers**: Types (ALB, NLB, ELB), listeners, health checks, TLS termination.
- **Logging & Monitoring**: Centralized log collection, metrics, dashboards, alerts.
- **Cost Awareness**: Pricing models, budgeting, tagging for cost allocation, optimization tools.

## Study Material References
- **IAM**: AWS IAM Best Practices – https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html
- **VPC**: Google Cloud VPC Overview – https://cloud.google.com/vpc/docs/overview
- **Security Groups**: Azure NSG Documentation – https://learn.microsoft.com/azure/virtual-network/network-security-groups-overview
- **Storage**: S3 Security – https://docs.aws.amazon.com/AmazonS3/latest/userguide/security.html
- **Load Balancers**: AWS Elastic Load Balancing – https://aws.amazon.com/elasticloadbalancing/
- **Monitoring**: Prometheus & Grafana – https://prometheus.io/docs/introduction/overview/
- **Cost**: AWS Cost Management – https://aws.amazon.com/aws-cost-management/

## Study Tips

1. **Map Request Flow** – Sketch how a request travels from the internet through load balancers, into VPC subnets, and finally reaches a compute service.
2. **Hands‑On Labs** – Spin up resources in a free tier account; experiment with IAM policies and observe the impact of permission changes.
3. **Misconfiguration Scenarios** – Review common pitfalls (e.g., overly permissive bucket policies, open security groups) and how they lead to breaches.
4. **Automation** – Practice writing IaC (Terraform/CloudFormation) for these resources to solidify understanding.
