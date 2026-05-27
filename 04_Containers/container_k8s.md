# Container + Kubernetes Layer

This layer covers containerization and orchestration fundamentals critical for modern DevSecOps.

## Core Topics

- **Dockerfiles**: Base images, layers, best‑practice instructions, multi‑stage builds.
- **Image Layers**: How layers are cached, size optimization, security implications.
- **Registries**: Public (Docker Hub) vs private registries, authentication, scanning images on push.
- **Kubernetes Pods**: Pod spec, containers, init containers, lifecycle hooks.
- **Services**: ClusterIP, NodePort, LoadBalancer, DNS service discovery.
- **Ingress**: Controllers, TLS termination, path‑based routing.
- **RBAC**: Roles, ClusterRoles, RoleBindings, least‑privilege access.
- **Network Policies**: Pod‑to‑pod traffic control, default deny, policy examples.
- **Resource Limits**: Requests vs limits, QoS classes, preventing resource starvation.
- **Admission Controllers**: Policy enforcement (PodSecurity, OPA Gatekeeper), mutating webhooks.

## Study Tips

1. **Hands‑On Labs** – Build a multi‑stage Dockerfile, push to a private registry, deploy with a simple Deployment and Service.
2. **Troubleshooting** – Use `kubectl describe`, `kubectl logs`, and `kubectl exec` to debug pod issues.
3. **Security Hardening** – Scan images with Trivy, enable PodSecurity policies, practice least‑privilege RBAC.
4. **Observe** – Inspect resource usage via `kubectl top` and set up alerts for OOM/killed pods.

## Study Material References
- **Docker Basics**: Docker Getting Started – https://docs.docker.com/get-started/
- **Kubernetes Documentation**: Kubernetes Concepts – https://kubernetes.io/docs/concepts/
- **K8s Security**: Securing a Cluster – https://kubernetes.io/docs/tasks/administer-cluster/securing-a-cluster/
- **Pod Security**: Pod Security Standards – https://kubernetes.io/docs/concepts/security/pod-security-standards/
