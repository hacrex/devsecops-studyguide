# CI/CD Layer

Focuses on building and deploying software safely and repeatably.

## Core Topics

- **Build Pipelines**: Stages (build, test, deploy), artifact management.
- **Deployment Stages**: Blue/green, canary, rolling updates.
- **Environment Variables & Secrets**: Secure storage, injection, rotation.
- **Secret Scanning**: Detecting hard‑coded credentials.
- **Dependency Scanning**: SCA tools, CVE databases.
- **Image Scanning**: Container image vulnerabilities, base image hygiene.
- **Approval Gates**: Manual approvals, policy enforcement.
- **Rollback Plans**: Versioning, automated rollback triggers.

## Study Tips

1. **Hands‑On CI** – Set up a simple pipeline in GitHub Actions or GitLab CI that builds, tests, and deploys a demo app.
2. **Security Policies** – Integrate tools like Trivy, Dependabot, or Snyk into the pipeline.
3. **Fail‑Fast** – Design pipelines to abort early on failures to save time and cost.
4. **Audit Trails** – Review pipeline logs for compliance and debugging.

## Study Material References
- **GitHub Actions**: Official Documentation – https://docs.github.com/en/actions
- **GitLab CI/CD**: GitLab Documentation – https://docs.gitlab.com/ee/ci/
- **Trivy Scanner**: Aqua Security Trivy – https://trivy.dev/
- **OWASP CI/CD Security**: CI/CD Top 10 – https://owasp.org/www-project-cicd-security-top-10/
